# System Cache Cleaner
A simple and automated shell script designed to clean up system cache and temporary files on macOS, Linux, and BSD platforms.
This tool helps users to free up disk space, remove unnecessary cached data, and improve system performance.

# 🚀 Features
- Automatically detect your operating system (macOS, Linux, BSD)
- Safely delete common cache directories and temporary files
- Special handling for macOS Xcode and browser caches
- Easy-to-use, one-line execution
- Fast and lightweight (pure Bash script)

# 📂 Supported Operating Systems
| OS Type |	Supported |	Cache/Temp Cleaning Scope |
| :-----: | :-------: | :-----------------------: |
| macOS	| ✅ | Caches, Logs, Trash, Xcode DerivedData, Safari & Chromium-based browsers cache |
| Linux |	✅ | User cache, system cache, temp directories, trash bin |
| BSD (FreeBSD, OpenBSD, NetBSD) ｜ ✅ ｜ System temp and cache directories, user cache |

# ⚙️ Usage
1. Download or clone this script
```bash
git clone https://github.com/YourRepo/System-Cache-Cleaner.git
cd System-Cache-Cleaner
```
2. Grant execution permission
```bash
chmod +x clean_cache.sh
``` 
3. Run the script
```bash
./clean_cache.sh
```

> [!WARNING]
> Use this script at your own risk.
> This script will permanently delete cache and temporary files without confirmation prompts.
> It is recommended to review and customize the script before running it, especially if you store important data in cache folders.

# ✅ Example Output
```
Checking system type...
Detected OS: Darwin
macOS system detected. Starting cache cleanup...
macOS cache cleanup completed!
```
# License
This project is open source and licensed under the MIT License.

