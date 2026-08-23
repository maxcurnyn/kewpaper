# kewpaper

A tiny Bash utility that uses the currently playing song's album artwork from [kew](https://github.com/ravachol/kew) as a [hyprpaper](https://github.com/hyprwm/hyprpaper) wallpaper.

## Examples

![Example 1](screenshots/20260822_19h04m34s_grim.png)

![Example 2](screenshots/20260822_19h05m09s_grim.png)

![Example 3](screenshots/20260822_19h05m25s_grim.png)

![Example 4](screenshots/20260822_19h05m45s_grim.png)

![Example 5](screenshots/20260822_19h06m36s_grim.png)

![Example 6](screenshots/20260822_19h08m16s_grim.png)

## Requirements

- Hyprland
- hyprpaper
- kew
- gdbus

## Installation

```bash
git clone https://github.com/maxcurnyn/kewpaper.git
cd kewpaper
chmod +x kewpaper
cp kewpaper ~/.local/bin/
```

Make sure `~/.local/bin` is in your `$PATH`.

The default monitor is `eDP-1`. Change it in the script if necessary.

## How to Use

Start kewpaper:

```bash
kewpaper
```

Stop kewpaper:

```bash
kewpaper stop
```

Restart kewpaper (stops the existing background loop and starts a fresh one):

```bash
kewpaper restart
```
