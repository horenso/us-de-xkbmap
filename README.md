# us-de-xkbmap
The keyboard layout I use on Linux.

# Features

It's an English (US) keyboard layout, with the addition that you can use `AltGr` to produce German characters:

<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd> => `Ö`

<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>A</kbd> => `Ä`

<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>u</kbd> => `Ü`

<kbd>AltGr</kbd> + <kbd>o</kbd> => `ö`

<kbd>AltGr</kbd> + <kbd>a</kbd> => `ä`

<kbd>AltGr</kbd> + <kbd>u</kbd> => `ü`

<kbd>AltGr</kbd> + <kbd>s</kbd> => `ß`

With some personal additions like the implication arrow:

<kbd>AltGr</kbd> + <kbd>i</kbd> => `→`

# How to try it?

Copy the map `jannis` (you are free to rename it of course) to `/usr/share/X11/xkb/symbols` and execute:

```
setxkbmap jannis
```
