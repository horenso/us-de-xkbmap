# us-de-xkbmap
The keyboard layout I use on Linux.

# Features

It's an English (US) keyboard layout, with the addition that you can use `AltGr` to produce German characters:

`AltGr + Shift + u` => `Ü`, `AltGr + u` => `ü`

`AltGr + Shift + o` => `Ö`, `AltGr + o` => `ö`

`AltGr + Shift + a` => `Ä`, `AltGr + a` => `ä`

`AltGr + s` => `ß`

With some personal additions like the implication arrow `→`
`AltGr + i` => `→`

# How to try it?

Copy the map `jannis` (you are free to rename it of course) to `/usr/share/X11/xkb/symbols` and execute:

```
setxkbmap jannis
```
