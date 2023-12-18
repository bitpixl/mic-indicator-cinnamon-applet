# Mic Indicator (Cinnamon Applet)

> Applet that allows to see and adjust the status of the current active microphone

# Last tested on Mint 21.2

#### Installation

```shell
$ git clone https://github.com/bitpixl/mic-indicator-cinnamon-applet
$ mkdir -p $HOME/.local/share/cinnamon/applets
$ mv mic-indicator-cinnamon-applet/mic-indicator@binatory $HOME/.local/share/cinnamon/applets/
$ # System Settings -> Applets -> Add "Mic Indicator" to a panel
```

The code is shamelessly stolen from [https://github.com/linuxmint/Cinnamon/blob/3.6.7/files/usr/share/cinnamon/applets/sound@cinnamon.org/applet.js](https://github.com/linuxmint/Cinnamon/blob/3.6.7/files/usr/share/cinnamon/applets/sound@cinnamon.org/applet.js)
