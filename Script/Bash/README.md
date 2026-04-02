# Utility Scripts Collection

A collection of Linux shell scripts designed to automate common system tasks.

## Table of Contents
- [backup_home.sh](#backup_homesh)
- [monitor_disk.sh](#monitor_disks)
- [cleanup_temp.sh](#cleanup_temps)
- [copy_multi.sh](#copy_multish)
- [report_system.sh](#report_systemsh)

## Scripts Overview

| Script Name        | Description |
|--------------------|-------------|
| `backup_home.sh`   | Creates compressed backups of the user’s home directory. |
| `monitor_disk.sh`  | Checks disk usage and alerts when thresholds are exceeded. |
| `cleanup_temp.sh`  | Removes temporary files older than a specified age. |
| `copy_multi.sh`    | Copies a file to multiple directories using a loop. |
| `report_system.sh` | Generates a system report with two argument modes. |

---

### backup_home.sh
Creates a timestamped `.tar.gz` backup of the user’s home directory.

**Usage:**
```bash
./backup_home.sh
