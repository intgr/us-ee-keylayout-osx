US/EE Keyboard Layout for K750
==============================

An U.S. keyboard layout with Estonian keys and the Euro-sign for Mac OS X.
I really dislike swapping keyboard layouts all the time and using the Estonian layout for programming is no good.

This is a "port" of the immensely useful "US keyboard with Estonian letters" Linux keyboard layout.

Additionally, the K750 modification swaps the §/± key found on Logitech K750 wireless keyboard for the regular ` and ~.

## Installation

```
mkdir -p ~/Library/Keyboard\ Layouts; \
  curl -Sso ~/Library/Keyboard\ Layouts/us_ee_k750.keylayout \
  https://raw.githubusercontent.com/intgr/us-ee-keylayout-osx/master/us_ee_k750.keylayout
```

## Differences from the Standard U.S. Layout

<table>
<tr><th>Key Combination</th><th>Character</th><tr>
<tr><td>⌥ + ]</td><td>õ</td></tr>
<tr><td>⌥ + '</td><td>ä</td></tr>
<tr><td>⌥ + ;</td><td>ö</td></tr>
<tr><td>⌥ + [</td><td>ü</td></tr>
<tr><td>⌥ + s</td><td>š</td></tr>
<tr><td>⌥ + z</td><td>ž</td></tr>
<tr><td>⌥ + e</td><td>€</td></tr>
<tr><td>⇧ + ⌥ + ]</td><td>Õ</td></tr>
<tr><td>⇧ + ⌥ + '</td><td>Ä</td></tr>
<tr><td>⇧ + ⌥ + ;</td><td>Ö</td></tr>
<tr><td>⇧ + ⌥ + [</td><td>Ü</td></tr>
<tr><td>⇧ + ⌥ + s</td><td>Š</td></tr>
<tr><td>⇧ + ⌥ + z</td><td>Ž</td></tr>
<tr><td>§</td><td>`</td></tr>
<tr><td>⇧ + §</td><td>~</td></tr>
</table>

Created with the wonderful Ukelele OS X keyboard layout editor.
