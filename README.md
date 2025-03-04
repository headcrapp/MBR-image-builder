# MBR-image-builder

## Read first:
The code used in this builer is not mine, i only modified it for convenience purposes.

## Usage:
This is basically a disk image builder which allows you to display a custom image on machine boot using VGA 13h mode (320x200px, 256 colors).
The disk image then can be used for whatever purpose you want (eg. converting it into a C array and embedding it into code to overwrite the MBR - for educational purposes only of course.)

The image you want to display **must be a** **320x200px .PNG file** and have **less than 256 colors**, else it's not going to work properly.
You simply put your desired image in the **Image** folder and run the **Create.bat** - it's automatically going to do everything for you and preview the image in MBR using QEMU.
No need to download any external programs as everything you need is already included in this .zip file.
