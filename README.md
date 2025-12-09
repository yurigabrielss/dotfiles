# Dotfiles — Arch Linux + Hyprland + GNU Stow

This repository contains my configuration files (dotfiles) for an Arch Linux environment running Hyprland.  
All configuration management is handled using **GNU Stow**, making the setup fully reproducible across machines with minimal effort.

> **Note:** This repository is not actively maintained. Use at your own discretion and always back up your existing configuration before applying these dotfiles.

**Disclaimer**: This repository is part of a personal study initiative.
The implementation focuses on exploring concepts and experimenting with techniques, and it should not be considered production-ready software.

---

## Technologies & Tools

- **OS:** Arch Linux  
- **Window Manager:** Hyprland  
- **Terminal:** Kitty  
- **Editor:** Neovim  
- **Status Bar:** Waybar  
- **Launcher:** Rofi  
- **System Info:** Fastfetch  
- **Dotfile Management:** GNU Stow  

---

## Screenshots

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/20cf9372-4ec1-4c1f-b54d-b74a36e41bb9" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/4ad10544-b3cf-4b94-a957-ff3559620d0c" />
<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/51496d19-5032-44b4-8d6b-b3d8c9e2d1f5" />

---

## Repository Structure

Each directory inside `dotfiles/` represents a standalone module managed via `stow`.

dotfiles/
hypr/
kitty/
waybar/
nvim/
rofi/
fastfetch/
gtk/


Applying a module:
stow <module>

This modular structure keeps the configuration organized, maintainable, and easy to replicate.
