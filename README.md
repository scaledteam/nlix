# nlix
UNIX-like operation system for wiremod addon.

## Features
Few workspaces on one chip.

Support many devices. For terminal you can use EGP Screen, Text Screen or Console screen as output device and Keyboard or Text Entry as output device.

Hotplug. Also after unconnecting device from port, device stay connected to system. It allow connect unlimited count of devices to limited count of ports.

Wireless connection using "wc" (require wiring addition).

Low system requires. Chip can use from 300 to infinitie ops and run with ultra low expression2 quotes. But if you set low ops limit, system will work slowly.

Modular filesystem. Nlix contain virtual filesystem "fstable", which represent tables as folders and other unit as files, and "fsreal", which allow to manipulate real files, using usual expression2 functions.

Input-output system. All program have their input and output, which you can redirect and make do interesting things.

Graphical system "X". Make programming with egp much comfortable, represent egp objects as class. You don't have to set egp id to every object manual, system X make it for you.

Combine few nlix chips in one system. Compution power of every chip will increases in proportion to the number of chips (require synchronization module).

Change programs code without reboot require synchronization module).

## Install
From site:

1. Download nlix using button "Clone or download"

2. Unpack archive "nlix-master.zip" папку:

```
$steamdir/steamapps/common/GarrysMod/garrysmod/data/expression2/
```

Where `$steamdir` - path to your Steam folder.

3. Rename nlix-master folder to nlix

4. Verify that the file is nlix.txt is located at this location:
```
$steamdir/steamapps/common/GarrysMod/garrysmod/data/expression2/nlix/nlix.txt
```

5. Done!

Using git git:

1. Join into directory:

```
$steamdir/steamapps/common/GarrysMod/garrysmod/data/expression2/
```

Where `$steamdir` - path to your Steam folder.

2. Write in terminal:

```
git clone https://github.com/scaledtm/nlix
```

3. Done!

## Using
1. Open Expression2 and choose nlix.txt in nlix folder, and create chip.

2. Connect EGP Screen to any port. Also you can connect keyboard, if you want work with text editor or virtual terminal.

If you want work with terminal, you can connect EGP Screen, Text Screen or Console Screen, and input device: Keyboard or Text Entry. Graphics mode have priority from terminal mode, therefore if you connect EGP Screen to your nlix chip, you must out from graphics mode (menu -> exit -> sh) or open virtual terminal (menu -> base -> xterm).

## Accessories
https://github.com/scaledtm/nlix-accessories/

Accessories set contains laptop, printer and projector for advanded duplicator 2, and also tool for building this things manual.

## Screenshots
http://steamcommunity.com/id/scaled/screenshots/
