# awesome
Custom theme and configuration files for Awesome WM

Theme files and rc.lua are based on Luca CPZ's work from [awesome-copycats](https://github.com/lcpz/awesome-copycats.git)

License: [BY-NC-SA](http://creativecommons.org/licenses/by-nc-sa/4.0)

* Configuration file is based on [awesome-copycats](https://github.com/lcpz/awesome-copycats.git)
* Awesome theme is based on [awesome-copycats](https://github.com/lcpz/awesome-copycats.git):
  * main theme file based on powerarrow theme
  * awesome icons comes from multicolor theme
* Gtk icon theme and awesome launchbar icons: [Flat Remix](https://github.com/daniruiz/flat-remix)
* Wallpaper: from [here](https://xshyfc.com/cool-wallpaper-3d.html/cool-wallpaper-3dwidescreen-cool-wallpaper-3d-1920x1200-high-resolution-pic-wpxh348799?lang=fr)
* Font: Terminus


Tested on Debian Buster. To work without modification, the following are required:
* Compton as compositing manager
* Xfce4-terminal
* unclutter firefox scrot mpd mpc dmenu xsel xlock (same as awesome-copycats)
* Software in launchbar are: Xfce4-terminal, Firefox, Emacs, Thunar, Gimp, Darktable, Audacious
* To use reboot/shutdown in menu with sudo without password, edit your `/etc/sudoers` file with `visudo` command and add the following line: `<your username>  ALL=(ALL) ALL,NOPASSWD: /sbin/reboot,/sbin/poweroff`

## Screenshots
![screenshot menu](/screenshots/screenshot_menu.jpg?raw=true "Background, widgets and menu")
![screenshot Emacs + Terminal + Thunar + calendar widget](/screenshots/screenshot_windows.jpg?raw=true "Emacs, terminal, thunar and calendar widget popup")