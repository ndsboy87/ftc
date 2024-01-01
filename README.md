# FBI

FBI is an open source title manager for the 3DS.

Download: https://github.com/Steveice10/FBI/releases

Requires [devkitARM](http://sourceforge.net/projects/devkitpro/files/devkitARM/), along with 3ds-curl, 3ds-zlib, and 3ds-jansson from the devkitPro pacman repository, to build.

# Features

* Browse and modify the SD card, TWL photos, TWL sounds, save data, and ext save data.
* Export, import, and erase save data from DS cartridges.
* Export, import, and delete save data secure values.
* Install titles/tickets from a file system, over a local network, or over the Internet with a URL or QR code.
  * Automatically imports title seeds on installation, either from the Internet or the SD card.
* Browse and delete pending titles (downloaded updates, in-progress eShop titles, etc).
* Customize appearance by placing replacements for RomFS resources in "sdmc:/fbi/theme/".

* Only available when run from a CIA, 3DS, or a 3DSX under Luma3DS:
  * Browse and modify CTR NAND, TWL NAND, and system save data.
  * Dump the raw NAND image to the SD card.
  * Launch titles installed to the system.
<br>
These are original FBI Features.

# Copy and Build

Use this bat code, run it in root dir/C:\
```bat
mkdir Projects
cd Projects
git clone https://github.com/ndsboy87/ftc.git
```

Citra:
```bat
make citra
```

3DS Hardware:
```bat
make
```

Clear previous build:
```bat
make clear
```

# Valid Credit (FTC)

SPI Protocol Information: [TuxSH](https://github.com/TuxSH/) ([TWLSaveTool](https://github.com/TuxSH/TWLSaveTool))

Thanks to every contributor and the creator of FBI for making FTC possible.
