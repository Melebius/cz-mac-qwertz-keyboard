# Czech QWERTZ Macintosh keyboard layout

While using Apple Macintosh for several years, I accustomed to its Czech keyboard
which can be used for both programming and proper typography typing.
When I started to use Linux as my main desktop platform,
I was missing the Czech Mac’s keyboard usability.

Therefore I created this keyboard layout…

## Features

This layout is derived from the `Czech (QWERTY, Macintosh)` keyboard layout
present in Ubuntu with a few changes:

- swap `Y` and `Z` keys to get a more common Czech keyboard layout
- add `\` and `|` symbols to `Q` and `W` keys (with `AltGr`)
  as they are difficult to type otherwise on an ANSI keyboard

## Installation

Apply `cz-mac-qwertz-keyboard.xkb.patch` to the `/usr/share/X11/xkb` folder.

Warning: This patch was created on Ubuntu 22.04 and may not work elsewhere
unless modified accordingly.

