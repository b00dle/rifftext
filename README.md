# rifftext

**A markdown editor with style.**

rifftext is a fork of [ReText](https://github.com/retext-project/retext) extended with runtime theme switching, modern design presets, and enhanced workflow features for developers and writers.

## Features

- **Dark theme** - Polished dark mode optimized for long coding sessions
- **Live preview** - Side-by-side editor with GitHub-style rendering
- **Powered by PyQt6** - Fast, native, cross-platform
- **Extensible** - Built on Qt with QSS styling support

## Quick Start

```bash
# Install dependencies
pip install PyQt6 PyQt6-WebEngine chardet Markups[markdown]

# Run rifftext
python rifftext.py yourfile.md
```

## Development

```bash
# Clone
git clone https://github.com/b00dle/rifftext.git
cd rifftext

# Install dev dependencies
pip install -e .

# Run from source
python rifftext.py
```

## Credits

rifftext is built on the excellent [ReText](https://github.com/retext-project/retext) by Dmitry Shachnev and Maurice van der Pot. See [ReText's original README](README/retext-README.md) for upstream details.

**Authors:** b00dle & riff
**License:** GPL v2+ (inherited from ReText)

## Roadmap

- [x] Dark theme with QSS styling
- [ ] Additional themes (Coder, Material available in themes/)
- [ ] Folder navigation sidebar
- [ ] Markdown link preview on hover
- [ ] Plugin system

---

*Built for makers, writers, and developers*
