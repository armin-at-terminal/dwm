README

DWM - THE DYNAMIC WINDOW MANAGER
================================
dwm is a fast and minimal window manager for X.

REQUIREMENTS
============
A "C" language compiler (gcc)

the "st" terminal

dmenu application launcher

INSTALLATION
============
$ git clone https://github.com/armin-at-terminal/dwm.git
$ cd dwm
# sudo make clean install

HOW TO START DWM
================
If you have a display manager (GDM, LightDM, SDDM), then just select dwm in the desktop select drop down menu.
If you instead are using startx, put the following into the .xinitrc file:

exec dwm

EXTRA FEATURES
==============
- gaps around windows
- dwindle and spiral layouts (incompatible with gaps)
- ability to resize floating windows from all corners
- ~/.dwm/autostart.sh will be executed every time dwm starts

KEYBOARD SHORTCUTS
==================
Modkey = super/windows key

mod + d = start dmenu
mod + return = start st
mod + b = toggle bar
mod + j = move up in the stack
mod + k = move down in the stack
mod + i = add 1 window to the master stack
mod + p = remove 1 window from the master stack
mod + h = move the master factor to the left
mod + l = move the master factor to the right
mod + shift + return = set focused window as master
mod + tab = swap between the last 2 tags
mod + shift + q = kill focused window
layouts
<
mod + t = master & stack
mod + f = floating
mod + m = fullscreen
mod + g = spiral (no gaps)
mod + o = dwindle (no gaps)
>
mod + space = toggle last workspace
mod + shift + space = toggle floating
mod + comma(,) = focus monitor left
mod + period(.) = focus monitor right
mod 1-9 = move to workspace 1-9
mod + 0 = view all tags
