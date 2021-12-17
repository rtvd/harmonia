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
xterm 
```

## Colour Schemes

Please download here:

* [Xresources file](Xresources-harmonia-day) for "Harmonia day" (dark text on light background)
* [Xresources file](Xresources-harmonia-night) for "Harmonia night" (light text on dark background)