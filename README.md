# 📦 Go-Nexus CLI

**Version:** vX.Y.Z  
**Release Date:** _<date>_

## 🚀 Overview
Go-Nexus is a powerful CLI tool for managing **Nexus Repository Manager**, enabling seamless interaction with repositories, components, and blob storage.

## 🔥 Features
- 📂 **Repository Management**: Create, delete, export, and import repositories.
- 🔐 **User & Access Control**: Change admin password, enable/disable anonymous access.
- 📦 **Component Management**: Upload, delete, and list artifacts (supports `raw`, `maven`, `docker`, `npm`, and more).
- 💾 **Blob Storage Handling**: Manage S3 and file-based blob stores.
- ⚙️ **Config Generation**: Auto-generate `conf.yaml` with connection settings.

## 🛠 Installation & Usage

### 1️⃣ Download the Binary
- 🐧 **Linux**: `go-nexus-linux-amd64`
- 🍏 **macOS (Universal)**: `go-nexus-darwin-universal` (x86_64 + ARM)
- 🏁 **Windows**: `go-nexus-windows-amd64.exe`

### 2️⃣ Make the Binary Executable (Linux/macOS)
```sh
chmod +x go-nexus-linux-amd64
```

### 3️⃣ Configure (Optional)
```sh
./go-nexus-linux-amd64 gencfg
```

### 4️⃣ Run Commands
```sh
./go-nexus-linux-amd64 repo ls  # List all repositories
./go-nexus-linux-amd64 upfile my-repo ./file.txt /target/path
```

## 📚 Documentation
For a full list of commands, run:
```sh
./go-nexus-linux-amd64 --help
```

## 📜 Configuration (`conf.yaml`)
Example configuration:
```yaml
url: "http://repo.example.com"
username: "admin"
password: "your-password"
```

## ⚠️ Important
Ensure you have administrator privileges on Nexus before using this tool.

## 💡 Feedback
Found a bug or have a feature request? Open an **issue** in the repository!

