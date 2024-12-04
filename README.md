VIEW CHANGELOG AT THE BOTTOM

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
- **Makes use of the new "sudo" command on windows 24H2***: required to use sudo ./aipm.exe to use the app
  
## Requirements

- Windows OS 24H2 and later.
- Potato PC supported

### Example Commands

To install a package:

```bash
sudo ./aipm.exe install <package_name>
```

Info on installer:
```bash
sudo ./aipm.exe info
```


# AtlasInstall Package Manager for Linux

AtlasInstall Package Manager (AIPM) is a simple command-line tool designed to download, extract, and install packages on Linux. The tool connects to a remote repository and fetches ZIP files to a specified directory. It includes the following features:

- Download packages from a GitHub repository ([AtlasPackages](https://github.com/NanoSoftDevTeam/AtlasPackageManager)).
- Extract the downloaded ZIP files to a specified directory (/usr/bin/AIPM/).
- Automatically create the installation directory if it doesn't exist.

## Features

- **Simple command-line interface**: Provides easy commands for installing and getting information.
- **Automatic directory creation**: If the target directory doesn't exist, it gets created automatically.
- **Requires the command "sudo" on linux***
  
## Requirements

- Any linux OS.
- Potato PC supported
- unzip program:
```bash
sudo apt install unzip
```

### Example Commands

To install a package:

```bash
sudo aipm install <package_name>
```

Info on installer:
```bash
aipm info
```

# Changelog
update 1.0.0 - initial release
update 1.1.0 - added update@self command for windows
