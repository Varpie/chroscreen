# croscreen

**WARNING: This project is deprecated and not maintained since xrandr is not usable with ChromeOS** (see issue #2 for more infos)

A small bash utility to easily change your brightnesst/gamma/backlight on Chrome OS
```
Usage : sh chroscreen [OPTION]...
	Options:
	  -v, --verbose           Prints useful informations
	  -g, --gamma R:G:B       Changes the gamma through xrandr
	      --brightness NUM    Changes the brightness through xrandr
	                          only use it with NUM > 1, -b should be used otherwise
	  -r, --reset             Resets xrandr values
	  -b, --backlight NUM     Changes the backlight (1 ≤ NUM ≤ 256)
	  -t, --temperature NUM   Experimental (understand: buggy) (1000 ≤ NUM ≤ 40000)
	  -h, --help              Display help
```
