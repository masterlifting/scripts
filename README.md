# Scripts Collection

A collection of useful automation scripts for system maintenance and productivity.

## 📁 Directory Structure

```
scripts/
├── README.md
└── powershell/
    └── windows_cleanup.ps1
```

## 🚀 Scripts Overview

### PowerShell Scripts

#### `windows_cleanup.ps1`
A comprehensive Windows 11 system cleanup script that safely removes temporary files, caches, and other system junk to free up disk space.

**Features:**
- ✅ Safe cleanup with error handling and path validation
- 🔍 Removes VS Code cache and temporary files
- 🌐 Cleans browser caches (Microsoft Edge)
- 🔧 Development tools cleanup (npm, Playwright, Postman, Docker)
- 📱 Application data cleanup (Thunderbird, Mozilla, Zoom, Ledger Live)
- 🗑️ System temporary files and Windows Update cache
- ♻️ Recycle Bin and thumbnail cache cleanup
- 📊 Registry cleanup for invalid startup entries
- 📈 Large file detection (files >100MB)
- 🧹 Windows system maintenance (Prefetch, Error Reporting, etc.)

**Requirements:**
- Windows 11 (or Windows 10)
- Administrator privileges
- PowerShell execution policy bypass (handled automatically)

**Usage:**
```powershell
# Run as Administrator
.\powershell\windows_cleanup.ps1
```

**Safety Features:**
- Checks for Administrator privileges
- Validates paths before deletion
- Comprehensive error reporting
- Skips non-existent files/folders
- Color-coded output for easy monitoring

## 🛡️ Safety Notes

- All scripts include safety checks and error handling
- Always run scripts as Administrator when required
- Review script contents before execution
- Scripts are designed to be safe but use at your own discretion

## 🤝 Contributing

Feel free to add new scripts or improve existing ones. Please ensure:
- Proper error handling
- Clear documentation
- Safety checks for destructive operations
- Cross-platform compatibility where applicable

## 📝 License

Personal use scripts - use responsibly.
