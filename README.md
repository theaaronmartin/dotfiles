# Dotfiles Backup

This repository contains my personal configuration files for **Neovim**, **WezTerm**, and **Starship**.

## 🚀 Installation Checklist

Follow these steps when setting up on a new machine.

### 1. Prerequisites (Install these first)
- [ ] **Git** (Required to clone this repo)
- [ ] **Nerd Font** (Required for icons in WezTerm/Starship)
    - *Recommendation:* [JetBrainsMono Nerd Font](https://www.nerdfonts.com/font-downloads)
    - *Action:* Download, unzip, and install the font files (Select all > Right Click > Install).
- [ ] **Ripgrep** (Required for Neovim Telescope searching)
    - *Windows:* `winget install BurntSushi.ripgrep.MSVC`
    - *Linux:* `sudo apt install ripgrep` (or equivalent)
- [ ] **C Compiler** (Recommended for Neovim Treesitter)
    - *Windows:* `winget install LLVM` (or install Visual Studio Build Tools)
    - *Linux:* `sudo apt install build-essential`

### 2. Core Apps
- [ ] **Neovim** (Text Editor)
- [ ] **WezTerm** (Terminal Emulator)
- [ ] **Starship** (Shell Prompt)

### 3. Clone & Link
Clone this repository to your home folder:
```bash
cd ~
git clone [https://github.com/YOUR_USERNAME/dotfiles.git](https://github.com/YOUR_USERNAME/dotfiles.git)
