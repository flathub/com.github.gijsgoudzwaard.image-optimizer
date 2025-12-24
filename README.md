# Image Optimizer

___Simple lossless image compression___

Compress your images with ease without the cost of loosing the images quality using JpegOptim and OptiPng.

Features:
- Compress bmp, jpg / jpeg, png, pnm and tiff with lossless compression
- Works offline, always ready where and whenever needed
- A clean interface, optimize your images effortlessly
- Easily quit the application by pressing Ctrl + Q

---

## Manual Install and Run

Make sure you follow the [setup guide for your Linux distribution](https://flathub.org/en/setup) before installing.

```
flatpak install flathub com.github.gijsgoudzwaard.image-optimizer
flatpak run com.github.gijsgoudzwaard.image-optimizer
```

## Building

```
git clone git@github.com:flathub/com.github.gijsgoudzwaard.image-optimizer.git
flatpak run org.flatpak.Builder build-dir --user --ccache --force-clean --install com.github.gijsgoudzwaard.image-optimizer.json
```

---

**Technologies**: GNOME, GTK3, Granite, Vala
