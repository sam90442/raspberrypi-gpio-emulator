# raspberry-gpio-emulator

RPi.GPIO emulator (untested)

# Require

- Python 3.7.7

# Install

```bash
$ pip install git+https://github.com/x/xxx/
```

# API

```python
import RPi.GPIO as GPIO
```


# Plugin

You can use plugins which you wrote.
List plugin modules which have create_plugin() function.
Plugin observe change event.

```
$ python sample_plugin.py sample_plugin_a sample_plugin_b
```


# Credit

This project based on [Pi GPIO Emulator](https://sourceforge.net/projects/pi-gpio-emulator/).

- [Roderick Vella](https://roderickvella.wordpress.com/2016/06/28/raspberry-pi-gpio-emulator/)
- 2016
- [Pi GPIO Emulator](https://sourceforge.net/projects/pi-gpio-emulator/)
- This project uses base design as reference, but it changes usage and implementation.

Modified by github user nosix:

- [https://github.com/nosix/raspberry-gpio-emulator/](https://github.com/nosix/raspberry-gpio-emulator/)

The latest version:
- Removed graphical interface for use with pytest to prevent errors
