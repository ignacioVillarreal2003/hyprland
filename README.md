# hyprland

Mi configuración personal de [Hyprland](https://hyprland.org/), tema **Tokyo Night**.

## Estructura

```
hypr/
├── hyprland.conf   # monitores, programas, autostart, look & feel, binds, window rules
├── hyprlock.conf   # pantalla de bloqueo
├── hypridle.conf   # timeouts de idle (dim, lock, dpms, suspend)
└── hyprpaper.conf  # wallpaper (deshabilitado por defecto, fondo sólido)
```

## Instalación

```bash
ln -sfn ~/dev/config/hyprland/hypr ~/.config/hypr
hyprctl reload
```

## Paleta (Tokyo Night)

| Nombre        | Hex       |
|---------------|-----------|
| bg            | `#1a1b26` |
| bg_dark       | `#16161e` |
| bg_highlight  | `#292e42` |
| fg            | `#c0caf5` |
| comment       | `#565f89` |
| blue          | `#7aa2f7` |
| cyan          | `#7dcfff` |
| purple        | `#bb9af7` |
| green         | `#9ece6a` |
| red           | `#f7768e` |
| orange        | `#ff9e64` |
| yellow        | `#e0af68` |