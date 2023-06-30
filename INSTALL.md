### [wob](https://github.com/dracula/wob)

A simple theme for wob, the color code of the bar is :

- Purple between 0 and 100
- Red in overflow
- Dark blue when muted style are send

#### Install using Git

If you are a git user, you can install the theme and keep up to date by cloning the repo:

```bash
mv ~/.config/wob ~/.config/wob.bak # backup your current wob config if you have one
git clone https://github.com/dracula/wob.git ~/.config/wob # clone this repo to wob config directory
```

#### Install manually

Download using the [GitHub .zip download](https://github.com/dracula/wob/archive/master.zip) option and unzip them.

#### Activating theme

There are two choices, the horizontal bar and the vertical bar (see screenshot).  
For the vertical bar, you need to install [wob](https://github.com/francma/wob) in a version higher than 0.14.2 or compile from the master branch.

To activate a theme, simply create a symbolic link to the theme file in the wob configuration directory.  
You must restart wob after activating or modifying the theme file.

```bash
ln -s ~/.config/wob/wob_horizontal.ini ~/.config/wob/wob.ini # for horizontal bar
ln -s ~/.config/wob/wob_vertical.ini ~/.config/wob/wob.ini # for vertical bar
```

_If you intend to modify it but want to keep it up to date, without conflict during a git pull, you can copy the theme file instead of making a symbolic link._

#### Configuration

Once you've installed and activated your chosen theme variant, you can configure it by editing the `~/.config/wob/wob.ini` file.
All available options are documented in the theme file itself.
