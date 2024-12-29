###  Installation

```bash
sudo pacman -S waybar
```

### Configuration

Clone this repository - _(No need to do this if you already did)_
```bash
git clone https://github.com/gb8462/Hyprland-Configs.git
```

Create a waybar directory then copy the config file to your waybar directory
```bash
mkdir ~/.config/waybar
cp Hyprland-Configs/waybar* ~/.config/waybar
```

Or

```bash
mv Hyprland-Configs/waybar ~/.config
```
This will move the waybar directory and its configs to your `~/.config`


### Font missing?

Run:

```bash
sudo pacman -S noto-fonts noto-fonts-emoji noto-fonts noto-fonts-cjk ttf-font-awesome
```