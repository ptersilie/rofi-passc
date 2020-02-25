# rofi-passc

A custom mode for rofi which displays passwords from
[pass](https://www.passwordstore.org/) and copies them to the clipboard.
Inspired by
[passmenu](https://git.zx2c4.com/password-store/tree/contrib/dmenu). If you are
looking for additional functionality you may want to check out
[rofi-pass](https://github.com/carnager/rofi-pass).

## Installation

Download the script `rofi-passc` or clone this repository, then add a new
mode to your rofi config, e.g.:

```
rofi.modi: window,drun,ssh,pass:~/PATH_TO_SCRIPT/rofi-passc
```
