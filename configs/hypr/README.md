### Setting up wallpaper

Install Hyprpaper

```bash
sudo pacman -S hyprpaper
```
Make a config file
```bash
touch ~/.config/hypr/hyprpaper.conf
```
Edit your config file -_(Use any text editor you want)_
```bash
vim ~/.config/hypr/hyprpaper.conf
```

write this inside your config file -_(remove the string and replace it with your actual path)_
```bash
preload = /home/"yourUser"/"path/to/your/wallpaper.png"
wallpaper = , /home/"yourUser"/"path/to/your/wallpaper.png"
```

Or

Move this config to your hypr config file -_(Then replace it with your actual path to your wallpaper)_
```bash
mv Hyprland-configs/hypr/hyprpaper.conf ~/.config/hypr
```