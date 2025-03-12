# kba

`kba` - keyboard backlight animation

# Dependencies

- `arecord`
- `brightnessctl`

# Installation

1. Clone repository and copy script file:
```
git clone https://github.com/ilya-grigoriev/kba && cd kba
chmod +x ./kba
mkdir -p $HOME/bin
cp kba $HOME/bin
```

2. Export `$HOME/bin` to your `$PATH`.

# Usage

To select device and class name, you need to read [this article](https://wiki.archlinux.org/title/Keyboard_backlight).

# Hacking

If you want to change fading speed, then change value of `sleep` command in `run_fading` function.

If you want to change brightness for music animation, then change volume or multiplier `10` in `run_music_animation` function to other.
