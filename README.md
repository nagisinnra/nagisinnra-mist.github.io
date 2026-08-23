# NagisinnraLinux‑mist
A world‑themed edition of NagisinnraLinux — designed around **blue, fog, silence, and minimalism**.

NagisinnraLinux‑mist is a special variant of NagisinnraLinux that applies a unified
“blue fog” aesthetic across the entire system.  
It preserves the lightweight and fast performance of the original distribution,
while delivering a fully immersive visual experience from the moment the system boots.

---

## Features

### Mist‑exclusive theme
- Custom LightDM theme with blue‑fog visuals  
- Unified wallpaper inspired by silent blue nebulae  
- Mist‑optimized GTK and Xfce themes  
- Contrast tuned for dark‑room environments

### Mist panel configuration (via XDG)
The panel layout is provided under:
`/etc/xdg/xfce4/panel/`  
This ensures the Mist UI is applied immediately on first boot, without relying on user configuration.

### Full skel integration
Mist’s initial user environment is applied through:
- `/etc/skel/.config/xfce4/xfconf/`
- `/etc/skel/.config/gtk-3.0/`

This guarantees that new users start with the complete Mist world‑theme intact.

###  Same lightweight performance as the original
- ISO size: ~2.4GB  
- RAM usage after boot: ~700MB  
- Debian Trixie base  
- Japanese input preconfigured (fcitx5 + Mozc)

---

## Technical Overview

- **Base**: Debian Trixie  
- **Desktop**: Xfce4  
- **Theme**: Mist (GTK / Xfce / LightDM)  
- **Panel**: Mist XDG configuration  
- **Wallpaper**: Mist fog‑blue background  
- **Initramfs**: Mist boot theme applied  
- **Skel**: Mist initial settings included

---

## ISO Download
(Place your GitHub Releases link here)

---

## Screenshots
(To be added)

---

## License
NagisinnraLinux‑mist follows the licenses of each Debian package.  
Mist theme assets are original works by the developer.

---

## World Concept
NagisinnraLinux‑mist is built around the concept of  
**“a silent blue galaxy floating inside the fog.”**

It is designed for dark‑room environments and aims to provide:
- Thin cold‑white lines  
- Fog‑like blue gradients  
- Quiet, minimal UI  
- A distraction‑free visual experience  

Mist is not just a theme — it is a **world‑edition** of NagisinnraLinux.

---

## Original Edition
NagisinnraLinux (Main Edition)  
https://nagisinnra.github.io
