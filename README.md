# rifftext

**A markdown editor with style.**

rifftext is a fork of [ReText](https://github.com/retext-project/retext) extended with a dark theme and enhanced workflow features for developers and writers.

## Features

- **Dark theme** - Polished dark mode optimized for long coding sessions
- **Live preview** - Side-by-side editor with GitHub-style rendering
- **Directory browser** - Separate tree view for folder navigation (WIP)
- **Powered by PyQt6** - Fast, native, cross-platform
- **Extensible** - Built on Qt with QSS styling support

## Quick Start

```bash
# Install dependencies
pip install PyQt6 PyQt6-WebEngine chardet Markups[markdown]

# Run with a file
python rifftext.py yourfile.md

# Run with a folder (opens directory browser)
python rifftext.py /path/to/folder
```

## Installation

### Add to PATH (CLI usage)

**Linux/macOS:**
```bash
# Add to ~/.bashrc or ~/.zshrc
export PATH="$PATH:/path/to/rifftext"

# Or create a symlink
sudo ln -s /path/to/rifftext/rifftext.py /usr/local/bin/rifftext
chmod +x /path/to/rifftext/rifftext.py
```

**Windows:**
```powershell
# Add rifftext directory to PATH
# Settings > System > About > Advanced system settings > Environment Variables
# Add "D:\Code\muxr\rifftext" to PATH

# Then use:
rifftext.py yourfile.md
```

### Build as standalone app

**Using PyInstaller:**
```bash
pip install pyinstaller

# Build single executable
pyinstaller --onefile --windowed --name rifftext rifftext.py

# Executable will be in dist/rifftext or dist/rifftext.exe
```

**Note:** Standalone builds will be ~250-350MB due to Qt/WebEngine dependencies.

## Development

```bash
# Clone
git clone https://github.com/b00dle/rifftext.git
cd rifftext

# Install in development mode
pip install -e .

# Run from source
python rifftext.py
```

## Credits

rifftext is built on the excellent [ReText](https://github.com/retext-project/retext) by Dmitry Shachnev and Maurice van der Pot. See [ReText's original README](README/retext-README.md) for upstream details.

**Authors:** b00dle & riff
**License:** GPL v2+ (inherited from ReText)

---

*Built for makers, writers, and developers*
