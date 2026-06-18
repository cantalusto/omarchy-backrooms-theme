# Omarchy Backrooms Theme

An [Omarchy](https://omarchy.org/) theme inspired by **The Backrooms** — dim olive
black, fluorescent cream, and that dry mustard-yellow wallpaper. You noclipped out
of reality and into your terminal.

![Backrooms theme](preview.png)

## Palette

| Role | Hex | |
|------|-----|--|
| Background | `#14140c` | dark olive black |
| Foreground | `#d8d2a8` | fluorescent cream |
| Accent | `#c2b54a` | dry mustard (the wallpaper) |
| Red | `#a64b3a` | rust |
| Green | `#7e8c44` | mildew olive |
| Slate | `#6e8499` | dim fluorescent blue |

## Install

```bash
omarchy-theme-install https://github.com/cantalusto/omarchy-backrooms-theme
```

Then pick **Backrooms** from the theme menu, or:

```bash
omarchy theme set "Backrooms"
```

## What you get

Everything applies **automatically** when you set the theme — it's built on
Omarchy's color templating, so there's nothing to copy by hand:

- Terminals (Alacritty, Ghostty, Kitty, Foot), Waybar, Mako, GTK, btop, SwayOSD,
  Hyprland borders, Hyprlock, Helix, Chromium, and more
- A custom **Walker** launcher — *Level 0 Terminal*: a dim yellow-room panel, a
  mustard "pill" on the selected entry, and a `CURRENT LEVEL: 0  ● STABLE`
  status strip along the bottom
- Neovim + VS Code use the warm **Gruvbox** scheme (olive/mustard, a perfect match)
- **Yaru-olive** icon theme
- Eight Backrooms wallpapers in `backgrounds/` (the classic yellow wallpaper loads
  as the default)

## Boot / Unlock screen

Apply the boot splash and reboot login via Omarchy's Unlock menu:

> Open the Omarchy menu → **Style → Unlock → Backrooms** (enter your password)

This sets the cream **"Backrooms" ASCII wordmark on dark olive** for both the
Plymouth boot screen and the SDDM login. It survives reboots and `omarchy update`.

## Updating

```bash
omarchy theme update     # git pulls every git-installed theme
omarchy theme set "Backrooms"
```

> Don't edit files inside `~/.config/omarchy/themes/backrooms/` directly —
> `omarchy theme update` runs `git pull` and your changes would block it.

## Wallpapers & credits

"The Backrooms" is community creepypasta lore. The `backgrounds/` images are
Backrooms community art / game screenshots, bundled for personal, non-commercial
use only. If you are a rights holder and want something removed, open an issue.

## License

Theme configuration files are released under the [MIT License](LICENSE).
This licence does **not** cover the bundled wallpapers/artwork (see above).
