# I3-WM Dotfiles ! :3 

![Preview](preview.png)

Minimalist i3wm configuration in blue and purple tones.

## Configuration Paths
- **Terminal:** `~/.config/alacritty/alacritty.toml`
- **Window Manager:** `~/.config/i3/config`
- **Status Bar:** `/etc/i3status.conf`

## Dependencies

### Gentoo
```bash
emerge x11-wm/i3 \
       x11-misc/i3status \
       x11-terms/alacritty \
       x11-misc/dmenu \
       media-fonts/jetbrains-mono \
       media-gfx/feh \
       x11-misc/xclip \
       x11-misc/autotiling
```

### Arch
```bash
pacman -S i3-wm \
          i3status \
          alacritty \
          dmenu \
          ttf-jetbrains-mono \
          feh \
          xclip \
          autotiling
```

### Void
```bash
xbps-install i3 \
             i3status \
             alacritty \
             dmenu \
             font-jetbrains-mono-otf \
             feh \
             xclip \
             python3-pip && \
             pip install autotiling
```

### Linux Mint / Ubuntu
```bash
apt install i3 \
            i3status \
            alacritty \
            dmenu \
            fonts-jetbrains-mono \
            feh \
            xclip \
            python3-pip && \
            pip3 install autotiling
```
---
