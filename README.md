# us-de-xkbmap
The keyboard layout I use on Linux.

# Features

It's an English (US) keyboard layout, with the addition that you can use `AltGr` to produce German characters:

<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>O</kbd> => `Ö`

<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>A</kbd> => `Ä`

<kbd>AltGr</kbd> + <kbd>Shift</kbd> + <kbd>U</kbd> => `Ü`

<kbd>AltGr</kbd> + <kbd>O</kbd> => `ö`

<kbd>AltGr</kbd> + <kbd>A</kbd> => `ä`

<kbd>AltGr</kbd> + <kbd>U</kbd> => `ü`

<kbd>AltGr</kbd> + <kbd>S</kbd> => `ß`

With some personal additions like the implication arrow:

<kbd>AltGr</kbd> + <kbd>I</kbd> => `→`

# How to try it?

Copy the map `jannis` (you are free to rename it of course) to `/usr/share/X11/xkb/symbols` and execute:

```
setxkbmap jannis
```
