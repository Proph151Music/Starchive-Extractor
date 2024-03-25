# Starchive-Extractor

## Description
Starchive Extractor is a Bash script designed to efficiently download, verify, and extract Starchive files from the Constellation Network. This tool is especially useful for handling large data files from different network clusters, providing a streamlined process for managing data integrity and storage.

## Features
- Download Starchive files from specified network clusters (mainnet, integrationnet, testnet).
- Verify file integrity using SHA256 hash checks.
- Extract Starchives with progress visualization.
- Check disk space before downloading to ensure sufficient storage.
- Interactive and non-interactive modes to facilitate automation.
- Customizable paths for data storage.

## Installation
Ensure you have `bash`, `curl`, `wget`, `pv`, `tar`, `sha256sum`, and `bc` installed on your system. Most of these tools are typically pre-installed on Linux systems.
If Starchiver detects that any of these dependencies do not exit, it will try to automatically install them.

1. Clone the repository:
   ```
   git clone "https://github.com/Proph151Music/Starchive-Extractor"
   ```
2. Navigate to the script directory:
   ```
   cd "Starchive-Extractor"
   ```
3. Make the script executable:
   ```
   chmod +x starchiver-ext
   ```

## Usage
Run the script with optional parameters to specify the data path and network cluster.

```
./starchiver-ext --data-path [PathToDataFolder] --cluster [Network]
```

- `--data-path`: Sets the path to the folder where Starchive files will be stored (`/var/tessellation/dag-l0/data`).
- `--cluster`: Specifies the network cluster to download Starchive files from (`mainnet`, `integrationnet`, `testnet`).

If no parameters are provided, the script enters an interactive mode, allowing you to choose options via a user-friendly menu.

## Requirements
- Linux Operating System with Bash Shell
- Internet Connectivity for Downloading Starchive Files
- Adequate Disk Space for Starchive Files

## Contributing
Contributions to the Starchive Extractor are welcome. Please follow the standard procedures for contributing to open source projects on GitHub.

## Acknowledgments
This script was written by @Proph151Music for the Constellation Network ecosystem. Don't forget to tip the bar tender! DAG Wallet Address for sending tips: `DAG0Zyq8XPnDKRB3wZaFcFHjL4seCLSDtHbUcYq3`
