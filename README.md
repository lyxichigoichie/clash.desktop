# clash.desktop
open clash as a desktop application

## How
modify the path in `Clash.desktop`
```
Exec=[path to your clash folder]/cfw
Icon=[path to your clash icon]/logo.png
```

copy the file `Clash.desktop` to `~/.local/share/applications` for user-wide
```
cp Clash.desktop ~/.local/share/applications/
```
or copy the file `Clash.desktop` to `/usr/share/applications` for system-wide
```
cp Clash.desktop /usr/share/applications
```
