# Harmonia for XTerm
(pre-alpha version)

## Installation

Programs like xterm use the traditional configuration method where configuration files are loaded into X11 system
via a program like xrdb. The precise way the configuration is done is specific to your Linux / UNIX system.

On some systems it is enough to put the content of Xresources file into .Xresources file in your home directory.
After that the files are loaded automatically upon starting an X11 session. Sadly, not every system does it.

For testing purposes, you can load the files manually and see if your xterm has loaded them up: 

```shell
cat Xresources-harmonia-day | xrdb
xterm +pc
```

*Note: `+pc` tells xterm to avoid PC behaviour where bold text is simulated by choosing a bright colour.
Any modern terminal running in a graphical environment (and perhaps even some working in a pure text mode)
should be capable of using actual bold fonts.*

## Colour Schemes

Please download here:

* [Xresources file](Xresources-harmonia-day) for "Harmonia day" (dark text on light background)
* [Xresources file](Xresources-harmonia-night) for "Harmonia night" (light text on dark background)