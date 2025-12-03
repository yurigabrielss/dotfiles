# 🌿 Yuri’s Dotfiles — Arch Linux + Hyprland + Stow

This repository contains my personal configuration files (dotfiles) for my Arch Linux environment running Hyprland — my first full ricing setup.  
All configuration management is handled using **GNU Stow**, allowing me to replicate this setup on any machine with just a few commands.
This repository is not actively maintained. Use with caution! Make a backup of your current setup before trying this out.

## 📦 Technologies & Tools

- **OS:** Arch Linux  
- **Window Manager:** Hyprland  
- **Terminal:** Kitty  
- **Editor:** Neovim  
- **Status Bar:** Waybar  
- **Launcher:** Rofi  
- **System Info:** Fastfetch  
- **Dotfile Management:** GNU Stow  

##📸 Screenshots
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/20cf9372-4ec1-4c1f-b54d-b74a36e41bb9" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4ad10544-b3cf-4b94-a957-ff3559620d0c" />


## 🗂 Repository Structure

Each directory inside `dotfiles/` represents an independent module managed via `stow`.

For example:

dotfiles/
hypr/
kitty/
waybar/
nvim/
rofi/
fastfetch/
gtk/

Applying a module is as simple as running:
stow <module>

This structure keeps the setup modular, easy to maintain, and fully reproducible.

