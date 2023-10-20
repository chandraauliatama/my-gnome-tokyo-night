# Specific Tokyo Night Theme For My PopOs

![image](https://github.com/chandraauliatama/my-gnome-tokyo-night/assets/64741857/036f7c06-d03b-4302-abca-7589ca0023e0)
![image](https://github.com/chandraauliatama/my-gnome-tokyo-night/assets/64741857/f99da353-79d8-4117-b17d-1e00dc8adf18)

## Information

chandraat@pop-os 

OS: Pop!_OS 22.04 LTS x86_64 

Host: 1701 Version 1.0 

Kernel: 6.5.4-76060504-generic 

Uptime: 3 hours, 9 mins 

Packages: 2027 (dpkg) 

Shell: zsh 5.8.1 

Resolutionesolution: 1920x1200 

DE: GNOME 42.5 

WM: Mutter 

WM Theme: Pop 

Theme: Tokyonight-Dark-B [GTK2/3] 

Icons: Tokyonight-Dark [GTK2/3] 

Terminal: x-terminal-emul 

CPU: AMD Ryzen 5 6600H with Radeon Graphics (12) @ 4.564GHz 

GPU: AMD ATI 03:00.0 Rembrandt 

Memory: 4349MiB / 15214MiB 



## Langkah Pemasangan
1. Pastikan sudah terinstall gnome-tweaks-tools
```
sudo apt install gnome-tweaks
```
2. Pastikan berada di themes directory yang benar
```
cd ~/.themes
```
3. Clone repository ini
```
git clone git@github.com:chandraauliatama/my-gnome-tokyo-night.git Tokyonight-Dark-B
```
atau
```
git clone https://github.com/chandraauliatama/my-gnome-tokyo-night.git Tokyonight-Dark-B
```
4. Buka aplikasi Tweaks dan set theme dan shells ke "Tokyonight-Dark-B"

## GTK 4 compatibilty
1. Take a GTK theme with GTK 4 compatibility

2. Copy the gtk.css for GTK 4 and paste it into ~/.config/gtk-4.0/
```
cp ~/themes/Tokyonight-Dark-B/gtk-4.0/gtk.css ~/.config/gtk-4.0/
```
3. Make any necessary color definitions for proper Libadwaita compatibility. The list of every defined color can be found [here](https://gitlab.gnome.org/GNOME/libadwaita/-/blob/main/src/stylesheet/_defaults.scss), with more info [here](https://gnome.pages.gitlab.gnome.org/libadwaita/doc/1.1/named-colors.html)

## Give Flatpak Permission to use GTK4
1. local: 
```
flatpak override --user --filesystem=xdg-config/gtk-4.0
```

2. global: 
```
flatpak override --filesystem=xdg-config/gtk-4.0

```

## Gnome Extension Actived
1. [Blur My Shells](https://extensions.gnome.org/extension/3193/blur-my-shell/)
    - Turn off panel blur option
2. [User Themes](https://extensions.gnome.org/extension/19/user-themes/)
3. [Pano Clipboard Manager](https://extensions.gnome.org/extension/5278/pano/)
4. Cosmic Dock
5. Cosmic x11 Gestures
6. Pop Shell
7. System76 Power
8. Ubuntu AppIndicators


### Extra(Useful Links)
1. [GTK 4 compatibility and flatpak info reddit](https://www.reddit.com/r/unixporn/comments/ts0dj2/gnome_and_they_said_theming_is_dead/)
2. [Tokyo Night Icon](https://www.gnome-look.org/p/1681475)
3. [Tokyo Night Theme](https://www.gnome-look.org/p/1681315)
