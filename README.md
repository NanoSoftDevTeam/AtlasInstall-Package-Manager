# AtlasInstall Package Manager for Windows

AtlasInstall Package Manager (AIPM) is a simple command-line tool designed to download, extract, and install packages on Windows using a progress bar window to track installation. The tool connects to a remote repository and fetches ZIP files to a specified directory. It includes the following features:

- Download packages from a GitHub repository ([AtlasPackages](https://github.com/NanoSoftDevTeam/AtlasPackageManager)).
- Extract the downloaded ZIP files to a specified directory (C:\AtlasIPM).
- Show a progress bar in a pop-up window while downloading.
- Automatically create the installation directory if it doesn't exist.

## Features

- **Simple command-line interface**: Provides easy commands for installing and getting information.
- **Progress tracking**: Displays a progress bar for package downloads and extraction.
- **Automatic directory creation**: If the target directory doesn't exist, it gets created automatically.
  
## Requirements

- Windows OS.
- Potato PC supported

### Example Commands

To install a package:

```bash
./aipm.exe install <package_name>
```

Info on installer:
```bash
./aipm.exe info
```
