# Brightness Controlling

```bash
xrandr -q

xrandr --output LVDS-1 --brightness 0.6
```

<!-- Custom Plugin for Brightness -->

> Or you can install a package for controling your system brightness

```bash
apt install brightnessctl brightness-udev
```

> Now you can contuol your brightness with those command

```bash
brightnessctl s 10%

brightnessctl s 100%
```

> And also you can create custom shortcut by using this operation

```bash
brightnessctl s 1%-

brightnessctl s 1%+
```

---
