# flungo's i3-config.d

These are my personal i3 configurations which I use in conjunction with the [i3-config.d](https://github.com/flungo/i3-config.d) script that I wrote. These can be used as example and inspriation for creating your own i3 configuration files whether you are using [i3-config.d](https://github.com/flungo/i3-config.d) or not.

## Usage

Individual configuration can be taken and placed into your `config.d` directory or used for inspiration of some of the configuration you can use. The configuration contents can be copied into your i3-config or you can use the [i3-config.d](https://github.com/flungo/i3-config.d) script to use these as intended. To use all configurations in your i3, run the following command (assuming your i3 config is in `~/.config/i3` and that you do not already have a `~/.config/i3/config.d` directory):

```
git clone https://github.com/flungo/i3-config.d-configs.git ~/.config/i3/config.d
```

## Configurations

* `00-base.conf` basic configurations for i3 setting up variables and allowing for minimal usability.
* `10-windows.conf` configurations for window management.
* `10-workspaces.conf` configurations for workspace management.
* `20-mouse.conf` configurations for using mouse with i3.
* `30-resize-mode.conf` resize mode configuration.
* `40-bar.conf` i3bar configuration.
* `40-xf86.conf` bindings for XF86 keyboard symbols.
* `50-i3lock.conf` i3lock configuration.
