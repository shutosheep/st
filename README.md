# Shuto's build of st (simple terminal)

This is my personal [st](https://st.suckless.org/) fork with some patches applied.

## Features

+ Scrollback with `Shift-PageUp/Down` or `Shift-MouseWheel`
+ [Gruvbox](https://github.com/morhetz/gruvbox) colors by default
+ Configure dynamically with Xresources values (will override default gruvbox colors)
+ Supports background transparency (note that it requires X composite manager like [picom](https://github.com/yshui/picom))
+ Minor visual improvments

## Installation

```
git clone https://github.com/shutosheep/st.git
cd st
cp config.def.h config.h
sudo make clean install
```

Configuration is done with `config.h`. Default values are stored in `config.def.h`.

## Applied patches

+ [alpha](http://st.suckless.org/patches/alpha/)
+ [boxdraw](https://st.suckless.org/patches/boxdraw/)
+ [clipboard](https://st.suckless.org/patches/clipboard/)
+ [externalpipe](https://st.suckless.org/patches/externalpipe/)
+ [font2](https://st.suckless.org/patches/font2/)
+ [gruvbox](https://st.suckless.org/patches/gruvbox/)
+ [scrollback](https://st.suckless.org/patches/scrollback/)
+ [xresources](https://st.suckless.org/patches/xresources/)
