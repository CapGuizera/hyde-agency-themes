Source archives for the HyDE theme patcher (theme.patch.sh).

These are extracted automatically when the theme is installed via:
    hyde-shell theme.patch.sh "Agency" "https://github.com/CapGuizera/hyde-agency-themes"

| Archive                       | Extracts to                  | Declared in hypr.theme |
| ----------------------------- | ---------------------------- | ---------------------- |
| Gtk_Agency.tar.gz             | ~/.local/share/themes        | $GTK_THEME=Agency      |
| Icon_Tela-circle-blue.tar.gz  | ~/.local/share/icons         | $ICON_THEME=Tela-circle-blue |

Notes:
- "Agency" is a self-contained GTK theme (does NOT overwrite HyDE's Wallbash-Gtk).
- "Tela-circle-blue" is from the Tela-circle icon set by vinceliuice (GPL-3.0).
- No cursor/font archives are shipped, so those follow your current HyDE defaults.
