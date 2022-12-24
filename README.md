# Dotfiles


| info  | = |
| ------------- | ------------- |
| Distro | Fedora 37 |
| WM | i3-Gaps |
| Font | Jetbrains Mono |
| Terminal | Kitty |
| colorscheme | Mountain | Paradise |
| Compositor |  [Pijulius picom](https://github.com/pijulius/picom) |


### Installing [picom](https://github.com/pijulius/picom)

```
# dnf install dbus-devel gcc git libconfig-devel libdrm-devel libev-devel libX11-devel libX11-xcb libXext-devel libxcb-devel mesa-libGL-devel meson pcre-devel pixman-devel uthash-devel xcb-util-image-devel xcb-util-renderutil-devel xorg-x11-proto-devel
$ cd /tmp && git clone https://github.com/pijulius/picom && cd picom
$ git submodule update --init --recursive
$ meson --buildtype=release . build
$ ninja -C build
# ninja -C build install
```

### GTK theme: [Mountain](https://github.com/mountain-theme/Mountain/)
              
### Icons: [zafiro](https://github.com/zayronxio/Zafiro-icons/releases)

### ZSH Theme: [zsh](https://github.com/pranaya2005/dotfiles)

### Credit
The credits are going towards adi1090x for the polybar & rofi themes, all I did was suiting it to be on my taste and do some minor integration for my distro:

* [Polybar](https://github.com/adi1090x/polybar-themes)
* [Rofi](https://github.com/adi1090x/rofi)

### Nvidia
* [guide](https://docs.fedoraproject.org/en-US/quick-docs/how-to-set-nvidia-as-primary-gpu-on-optimus-based-laptops/)

![picture1](https://user-images.githubusercontent.com/92778316/209409474-0c4b9612-efd0-4e48-9507-0af713f7b3db.png)
