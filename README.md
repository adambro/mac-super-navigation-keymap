Arrow keys with Super powers
===========================

MacOSX-like navigation keys binding for Linux users. Hold ``Super`` key (also known as ``Windows`` key) with arrows to make special moves:

* Left (Home)
* Right (End)
* Up (PageUp)
* Down (PageDown)

## Installation

Clone repository to your home directory:

`git clone https://github.com/adambro/mac-super-navigation-keymap.git ~/.xkb`

Then add following line to X11 startup script:

`xkbcomp -I$HOME/.xkb ~/.xkb/keymap/mykbd $DISPLAY`


## References

* [Solution on Unix stack exchange](http://unix.stackexchange.com/questions/65434/map-superleftright-to-home-end)
* [Extending the X keyboard map with xkb](http://madduck.net/docs/extending-xkb/)
* [Refence documentation on custom keyboard definitions in Ubuntu](https://help.ubuntu.com/community/Howto%3A%20Custom%20keyboard%20layout%20definitions)

