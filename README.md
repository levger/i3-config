# i3 config
This is my fairly minimal configuration for the [i3 tiling window manager](https://i3wm.org/). It replaces `~/.config/i3/config`.

## Main changes from vanilla
My changes can be found in the bottom of the config file:
- `vim` key bindings for navigation
- use a 1 pixel border instead of window title bars
- display dialogs/pop-ups in floating windows
- display the network manager applet (`nm-applet`) in the status bar
- enable automatic screen locking (via `xss-lock` & `i3lock`) ([found here](https://ermannoferrari.net/i3-config-file))

## Misc
I recommend swapping left alt and left windows key.
I also swapped capslock and escape and use right alt as compose key.
You can do this via `setxkbmap` in `~/.profile`:
```
setxkbmap -option altwin:swap_lalt_lwin -option caps:swapescape -option compose:ralt
```
