# Hyprland Config

Hyprland 0.55+ (Lua config) + Noctalia shell.

## Install

```sh
for d in hypr kitty matugen rofi waybar wlogout; do cp -r $d ~/.config/; done
cp starship.toml ~/.config/
cp .gtkrc-2.0 ~/
mkdir -p ~/.config/noctalia ~/.local/state/noctalia
cp noctalia/config.toml ~/.config/noctalia/
cp noctalia/settings.toml ~/.local/state/noctalia/   # theme (GUI settings)
```

Packages: hyprland, noctalia, kitty, matugen, rofi, grim, slurp, wl-clipboard, network-manager-applet, xdg-desktop-portal-hyprland.
