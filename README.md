# 📦 Nexus-CLI

**Version:** v1.0.0  
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
- 🐧 **Linux**: `nexus-cli-linux-amd64`
- 🍏 **macOS (Universal)**: `nexus-cli-darwin-universal` (x86_64 + ARM)
- 🏁 **Windows**: `nexus-cli-windows-amd64.exe`

### 2️⃣ Make the Binary Executable (Linux/macOS)
```sh
chmod +x nexus-cli
```

### 3️⃣ Configure (Optional)
```sh
./nexus-cli gencfg
```

### 4️⃣ Run Commands
```sh
./nexus-cli repo ls  # List all repositories
./nexus-cli upfile my-repo ./file.txt /target/path
```

## 📚 Documentation
For a full list of commands, run:
```sh
./nexus-cli --help
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

