# setup-theme-changer

Makes theme changing more fun and less time taking.

Just select the theme and it'll change it for every tools you use.

Watch this little demo:

![demo1](sc_vid/demo1.gif)

## currently supported tools

* **terminals:**
	- alacritty
	- termite
	- urxvt
* **Xresources:**
	- urxvt
	- polybar
* **Laucher:**
	- rofi
	- dmenu
* **Notification Daemon:**
	- dunst
* **WM:**
	- bspwm
* **bar:**
	- polybar
* **reader**:
	- zathura

> Support for dmenu automatic compilation will come soon, currently you have to manually compile dmenu after running this script


```
Note:
	This theme is heavily based on my setup of how keep my dotfiles.
	You also have to keep the colorschemes as individual file and base config(other config settings) on second file.
	To see how to do it, visit the below links.

	Also, only tools to which links are provided below require this type of seperate configuration.

	Reminding you, always keep backup of your config files.
```

* [alacritty](https://github.com/coolabhays/my-config-files/tree/master/.config/alacritty)
* [termite](https://github.com/coolabhays/my-config-files/tree/master/.config/termite)
* [Xresources](https://github.com/coolabhays/my-config-files/tree/master/.config/xresources_colors)


My config files for other tools are as follow:

* [rofi](https://github.com/coolabhays/my-config-files/tree/master/.config/rofi)
* [dmenu](https://github.com/coolabhays/my-config-files/tree/master/.config/)
* [dunst](https://github.com/coolabhays/dmenu_custom)
* [zathura](https://github.com/coolabhays/my-config-files/tree/master/.config/zathura)
* [bspwm](https://github.com/coolabhays/my-config-files/tree/master/.config/bspwm)
* [polybar](https://github.com/coolabhays/my-config-files/tree/master/.config/polybar)


## dependencies:

* gnu-sed
* fzf
* find
* tools which you want to change theme of

Also, if you are not using `fzf`(can't find fzf if in your `PATH`) then `select` will be used for theme choosing
