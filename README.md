# GtkTheme

## Description

Install and activate optically pleasing Gtk2/Gtk3 Themes.

## Usage

```yaml
- role: GtkTheme
  theme: "Ambiance"
```

## Configuration

*optional* `theme`: Gtk Theme to be used. Possible options "Ambiance" or "Radiance"
(Default: `Ambiance`).

*optional* `homedir`: Homedir of the user for which the theme should be
configured. (Default: `{{ ansible_env.HOME }}`).

*optional* `user`: Username of the user for which the theme should be
configured. (Default: `{{ ansible_env.USER }}`).
