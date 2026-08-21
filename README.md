# kewpaper

A tiny Bash utility that uses the currently playing song's album artwork from [kew](https://github.com/ravachol/kew) as a [hyprpaper](https://github.com/hyprwm/hyprpaper) wallpaper.

## Requirements

- Hyprland
- hyprpaper
- kew
- gdbus

## Installation

```bash
git clone <repo-url>
cd kewpaper
chmod +x kewpaper
cp kewpaper ~/.local/bin/

Make sure ~/.local/bin is in your $PATH.

The default monitor is eDP-1. Change it in the script if necessary.
