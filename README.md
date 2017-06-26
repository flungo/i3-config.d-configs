# flungo's i3-config.d

These are my personal i3 configurations which I use in conjunction with the [i3-config.d](https://github.com/flungo/i3-config.d) script that I wrote. These can be used as example and inspriation for creating your own i3 configuration files whether you are using [i3-config.d](https://github.com/flungo/i3-config.d) or not.

## Usage

Individual configurations can be taken and placed into your `config.d` directory or used as inspiration for your own configuration files. Feel free to take and use what you needs under the terms of the [LICENSE](./LICENSE).

### With i3-config.d
 
If you are using (or want to use) [i3-config.d](https://github.com/flungo/i3-config.d) and only wish to use some of the configurations, copy those of interest into your `config.d` directory or use them as inspiration for your own configuration files. To use all configurations in your i3, run the following command (assuming your i3 config is in `~/.config/i3` and that you do not already have a `~/.config/i3/config.d` directory):

```
git clone https://github.com/flungo/i3-config.d-configs.git ~/.config/i3/config.d
```

### Without i3-config.d

To use without [i3-config.d](https://github.com/flungo/i3-config.d), simply copy the contents (or even just sections of) the files into your own i3 `config` file, typically located at `~/.config/i3/config`.

## Configurations

* `00-base.conf` basic configurations for i3 setting up variables and allowing for minimal usability.
* `10-windows.conf` configurations for window management.
* `10-workspaces.conf` configurations for workspace management.
* `20-mouse.conf` configurations for using mouse with i3.
* `30-resize-mode.conf` resize mode configuration.
* `40-bar.conf` i3bar configuration.
* `40-xf86.conf` bindings for XF86 keyboard symbols.
* `50-i3lock.conf` i3lock configuration.
