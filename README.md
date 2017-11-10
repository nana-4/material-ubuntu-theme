# Material Ubuntu (draft name)

This is a soft fork of [Materia](https://github.com/nana-4/materia-theme) using [Ubuntu colour palette](https://design.ubuntu.com/brand/colour-palette/).

![theme](../images/theme.png?raw=true)
![theme-dark](../images/theme-dark.png?raw=true)
![theme-light](../images/theme-light.png?raw=true)

## Differences from Materia

- Most colours are based on the [Ubuntu colour palette](https://design.ubuntu.com/brand/colour-palette/).
- Using primary color for `scale` and `button.suggested-action`.
- Using accent color for `tab` and `button:checked`.
- Changing `.titlebar` background color when the window is inactive.
- Tweaking text opacities for the theme.

## Installation

```bash
git clone --depth 1 https://github.com/nana-4/material-ubuntu-theme.git
cd material-ubuntu-theme
sudo ./install.sh
cd .. && rm -rf material-ubuntu-theme
```

## Uninstallation

```bash
sudo rm -rf /usr/share/themes/Material-Ubuntu{,-compact,-dark,-dark-compact,-light,-light-compact}
```

## TODO & Known Issues

- `chrome`, `metacity-1`, `unity` and `xfwm4` themes are not adapted the colour palette for now.
- `scale` is indistinguishable when the background is selected.

For other bugs, see the Materia's Issue Tracker.

**NOTE:** Please do not report bugs that occur even with Materia. Please report them to [Materia's Issue Tracker](https://github.com/nana-4/materia-theme/issues).

## License

GPLv2+
