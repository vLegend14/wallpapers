# 🖼️ Wallpapers Collection

Personal curated collection of high-quality wallpapers for desktop and mobile devices.

## 📁 Categories
```
wallpapers/
├── 🎮 Shiny-colors-wallpapers/    # THE iDOLM@STER Shiny Colors
├── ⚔️  Solo-Leveling/              # Solo Leveling anime/manhwa
├── 🎌 anime/                       # General anime wallpapers
├── 🎯 arknights/                   # Arknights game art
├── 🌆 city/                        # Urban & cityscape
├── 🌃 cyberpunk/                   # Cyberpunk aesthetic
├── 🎮 genshin/                     # Genshin Impact
├── 🏯 japon/                       # Japanese culture & landscapes
├── 🐧 linux/                       # Linux-themed wallpapers
├── ✨ minimal/                     # Minimalist designs
├── 🌄 paisajes/                    # Landscapes & nature
├── 🎨 pixelart/                    # Pixel art wallpapers
├── 🪟 windows/                     # Windows-themed
├── ☄️  your-name/                  # Your Name (Kimi no Na wa) movie
├── 🎬 animatedWallpapers/          # Animated wallpapers (MP4)
└── 📦 varios/                      # Miscellaneous
```

## 🚀 Quick Start

### Clone this repository
```bash
git clone https://github.com/vLegend14/wallpapers.git
cd wallpapers
```

> **Note:** This repo uses **Git LFS** for large files (videos and high-res images).  
> Make sure you have Git LFS installed: https://git-lfs.github.com/

### Use a wallpaper

**Linux (GNOME):**
```bash
gsettings set org.gnome.desktop.background picture-uri "file://$(pwd)/anime/catpuccin_samurai.png"
```

**Windows (PowerShell):**
```powershell
reg add "HKCU\Control Panel\Desktop" /v Wallpaper /t REG_SZ /d "C:\Path\To\wallpapers\anime\catpuccin_samurai.png" /f
RUNDLL32.EXE user32.dll,UpdatePerUserSystemParameters
```

**macOS:**
```bash
osascript -e 'tell application "Finder" to set desktop picture to POSIX file "/path/to/wallpapers/anime/catpuccin_samurai.png"'
```

## 📊 Stats

- **Total wallpapers:** 234+ static images
- **Animated wallpapers:** 23 MP4 videos
- **Total size:** ~2.5 GB (with LFS)
- **Formats:** JPG, PNG, GIF, MP4

## 🎥 Animated Wallpapers

To use animated wallpapers, you'll need:

- **Linux:** [wallpaper-engine-kde-plugin](https://github.com/catsout/wallpaper-engine-kde-plugin) or [komorebi](https://github.com/cheesecakeufo/komorebi)
- **Windows:** [Lively Wallpaper](https://github.com/rocksdanister/lively) or [Wallpaper Engine](https://store.steampowered.com/app/431960/Wallpaper_Engine/)
- **macOS:** [Plash](https://github.com/sindresorhus/Plash) or [IINA](https://iina.io/)

## 📝 License

Personal collection for personal use. All wallpapers belong to their respective creators and copyright holders.

## 🤝 Contributing

Feel free to suggest wallpapers by opening an issue!

---

**Made with ❤️ for desktop rice enthusiasts**
