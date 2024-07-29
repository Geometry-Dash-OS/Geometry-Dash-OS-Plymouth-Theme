# Geometry Dash OS Plymouth Theme

This theme was forked from the [Monoarch plymouth theme](https://github.com/farsil/monoarch) on Github.

# Building

```
git clone https://github.com/geometry-dash-os/geometry-dash-os-plymouth-theme
cd geometry-dash-os-plymouth-theme
makepkg -s # if you want to install this theme, use makepkg -si instead.

# Only run this if you installed the theme and you want to set it as the current plymouth theme.
plymouth-set-default-theme -R geometry-dash-os-plymouth-theme
```
