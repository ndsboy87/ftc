# FTC

Download, if your a developer you should know by know how to make 3DS Homebrew, so theres no guide.

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

These are original FBI Features. FTC Features have yet to be added

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
