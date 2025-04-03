# System Cache Cleaner
A simple and automated shell script designed to clean up system cache and temporary files on macOS, Linux, and BSD platforms.
This tool helps users free up disk space, remove unnecessary cached data, and improve system performance.

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
> This script permanently deletes the cache and temporary files without confirmation prompts.
> Reviewing and customizing the script before running it is recommended, especially if you store important data in cache folders.

# ✅ Example Output
```
Checking system type...
Detected OS: Darwin
The macOS system is detected. Starting cache cleanup...
The macOS cache cleanup is completed!
```
# License
This open-source project is licensed under the MIT [License](LICENSE).

