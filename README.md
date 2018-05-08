# Nlix
UNIX-like operating system on Wiremod.

## Features
Multiple workspaces using just only one chip.

Support for many devices. To work with the terminal, you can use the EGP Screen, Text Screen or Console Screen as an output device and Keyboard or Text Entry as an input device.

Hotplug. Also, after disconnecting the device from the plug, it remains connected to the system. This behavior allows you to connect an unlimited number of devices to a limited number of plugs.

Wireless connection of external devices using **wc** program (requires the wiring extension to be enabled).

Low system requirements. The chip can use 300 or more ops and can run with ultra low Expression 2 quotas. But keep in mind that if you set low ops limit, the system will run slower than normal.

Modular file system. Nlix has a virtual file systems **fstable**, where tables represent folders and other data represent files, and **fsreal**, which allows to manipulate real files using standard Expression 2 functions.

I/O system. All programs have an input and output stream, which you can redirect and do a lot of interesting things.

Graphic system X. Makes work with EGP much comfortable, as it represents EGP objects as a class. You don't have to set the EGP IDs for each object manually, system X sets them for you.

Combining of multiple Nlix chips. The computing power of each chip increases the system's performance in an arithmetic progression (requires a synchronization module).

Changing the code of the programs without rebooting (requires a synchronization module).

## Installation
From the site:

1. Download Nlix using a "Clone or download" button.

2. Unpack the archive "nlix-master.zip" here:

```
$steamdir/steamapps/common/GarrysMod/garrysmod/data/expression2/
```

Where `$steamdir` is the path to your Steam folder.

3. Rename `nlix-master` folder to `nlix`

4. Make sure that the file `nlix.txt` is in this location:
```
$steamdir/steamapps/common/GarrysMod/garrysmod/data/expression2/nlix/nlix.txt
```

5. Done!

Using git:

1. Move to this directory:

```
$steamdir/steamapps/common/GarrysMod/garrysmod/data/expression2/
```

Where `$steamdir` is the path to your Steam folder.

2. Run this command:

```
git clone https://github.com/scaledTM/nlix.git
```

3. Done!

## Using
1. Open the Expression 2 editor and select nlix.txt in the nlix folder, then place the chip.

2. Connect an EGP Screen to any port. Also, you can connect the keyboard, if you want to work with a text editor or a virtual terminal.

If you want to work with the terminal, connect the I/O devices. Priority is given to the graphical mode, so if you connect the EGP Screen to your nlix chip, you need to exit the graphical mode (menu -> exit -> sh) or open the virtual terminal (menu -> base -> xterm).

## Accessories
https://github.com/scaledtm/nlix-accessories/

The accessory kit includes the laptop, printer and projector for Advanced Duplicator 2, and also tools for building them manually.

## Screenshots
https://steamcommunity.com/id/scaled/screenshots/?appid=4000
