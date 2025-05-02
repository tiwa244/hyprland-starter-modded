Ths script supports the following distributions:
* Arch Linux (+ Arch Linux based distros e.g., EndeavourOS, Manjaro, ...)
* Fedora Linux
* Nobara Linux
* more to come soon...

## Documentation (only this one.)
Just copy the following command into your terminal and execute. { testing for arch-based only! } 

```
sudo pacman -S git && cd ~ && git clone https://github.com/tiwa244/hyprland-starter-modded/tree/main/Hypr-starter-modded-main
```
> for testing purpose only! & Hyprland does not officially support NVIDIA hardware.

- Window Manager: hyprland 
- Status Bar: waybar 
- Launcher: rofi-wayland 
- Browser: Firefox
- Terminal: alacritty 
- Notification Service: dunst 
- File Manager: nautilus
- xdg-desktop-portal-hyprland 
- qt5-wayland 
- qt6-wayland 
- Lock screen: hyprlock

You can find all shipped configurations here: https://github.com/mylinuxforwork/hyprland-starter/tree/main/dotfiles

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
