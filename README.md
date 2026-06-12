# Agency Themes — HyDE

A collection of 4 themes for [HyDE](https://github.com/HyDE-Project/HyDE) (Hyprland) with an
intelligence-agency aesthetic: dark, navy, surveillance. Font: JetBrains Mono Nerd Font.

| Theme | Aesthetic | Accent |
|-------|-----------|--------|
| **Agency** (NSA) | dark navy, NSA seal | `#3b82f6` |
| **FBI** | dark navy, FBI seal | `#3b82f6` |
| **CIA** | dark navy, CIA seal | `#3b82f6` |
| **MI6** | dark teal, typographic | `#2dc9dc` (cyan) |

## Screenshots

Desktop — waybar with the TOP SECRET chip, solid blue active workspace:

![Desktop](screenshots/desktop.png)

Terminal — kitty + fastfetch with the per-theme agency logo and `capgz@blacksite` prompt:

![Terminal](screenshots/terminal.png)

Logout overlay (wlogout) following the theme palette:

![Wlogout](screenshots/wlogout.png)

## Wallpaper previews

| Agency | FBI |
|--------|-----|
| ![Agency](previews/agency.png) | ![FBI](previews/fbi.png) |

| CIA | MI6 |
|-----|-----|
| ![CIA](previews/cia.png) | ![MI6](previews/mi6.png) |

## Installation

With HyDE installed, run (one per theme you want):

```bash
hyde-shell theme.patch.sh "Agency" "https://github.com/CapGuizera/hyde-agency-themes"
hyde-shell theme.patch.sh "FBI"    "https://github.com/CapGuizera/hyde-agency-themes"
hyde-shell theme.patch.sh "CIA"    "https://github.com/CapGuizera/hyde-agency-themes"
hyde-shell theme.patch.sh "MI6"    "https://github.com/CapGuizera/hyde-agency-themes"
```

Then pick the theme with `SUPER+SHIFT+T`.

Each theme ships: color palette (`theme.dcol`), wallpapers (seal + watermark variant),
Hyprland border colors, waybar, kitty, rofi, kvantum, and an optional hyprlock layout in
"TOP SECRET // RESTRICTED ACCESS" style (applied when wallbash is in *Theme colors* mode).

## Notes

- The NSA, FBI and CIA seals are official US government insignia (public domain, sourced
  from Wikimedia Commons). They are used here decoratively, with no affiliation or
  endorsement implied.
- The SIS/MI6 crest is copyrighted; the MI6 theme uses a typographic composition instead.
- Themes are fully self-contained in the standard HyDE format: switching to other themes
  leaves no residue.

## License

MIT for the theme files. Seal images: public domain (US Gov).
