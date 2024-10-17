# Tailsmonster's ML4W Hyprland Starter 1.0.2

This has my tweaks to ML4W's Hyprland starter kit for my ideal workflow.

To make your start with Hyprland as simple as possible, you can find here an easy to use installation and configuration script.

![image](https://raw.githubusercontent.com/tailsmonster/My-MLFW-Hyprland/refs/heads/main/20241017_08h00m09s_grim.png)


## Requirements

Ths script supports the following distributions:
* Arch Linux (+ Arch Linux based distros e.g., EndeavourOS, Manjaro, ...)

## Documentation (Wiki)

You can find the complete documentation of the ML4W Dotfiles in the Wiki. <b>[Open the Wiki here](https://github.com/mylinuxforwork/hyprland-starter/wiki)</b>

## Installation

Just copy the following command into your terminal and execute.

```
bash <(curl -s https://raw.githubusercontent.com/tailsmonster/My-MLFW-Hyprland/main/setup.sh)
```

> Hyprland does not officially support NVIDIA hardware. But many users have reported a successful installation. Please read: https://wiki.hyprland.org/Nvidia/

## Packages

The script will install the following packages and the corresponding configurations:

- Window Manager: hyprland 
- Status Bar: waybar 
- Launcher: rofi-wayland 
- Browser: Firefox
- Terminal: alacritty 
- Notification Service: dunst 
- File Manager: Thunar
- xdg-desktop-portal-hyprland 
- qt5-wayland 
- qt6-wayland 
- Lock screen: hyprlock

You can find all shipped configurations here: https://github.com/tailsmonster/My-MLFW-Hyprland/tree/main/dotfiles

## Key Bindings

The following custom key bindings are enabled (can be customized in ~/.config/hypr/hyprland.conf)

- <kbd>SUPER</kbd> + <kbd>RETURN</kbd> to start terminal alacritty
- <kbd>SUPER</kbd> + <kbd>Q</kbd> to quit an application
- <kbd>SUPER</kbd> + <kbd>B</kbd> to start browser
- <kbd>SUPER</kbd> + <kbd>M</kbd> to exit Hyprland
- <kbd>SUPER</kbd> + <kbd>E</kbd> to start filemanager
- <kbd>SUPER</kbd></kbd> + <kbd>CTRL</kbd> + <kbd>RETURN</kbd> to start launcher rofi
- <kbd>SUPER</kbd> + <kbd>T</kbd> to toggle floating
- <kbd>SUPER</kbd> + <kbd>F</kbd> to toggle fullscreen
- <kbd>SUPER</kbd> + <kbd>1-9</kbd> to switch workspaces
- more key bindings in ~/.config/hypr/conf/binds.conf

or after the installation with right mouse click on Apps in the status bar.
