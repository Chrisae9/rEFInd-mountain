# rEFInd-Omen

A clean mountain theme for the [rEFInd UEFI boot manager.](http://www.rodsbooks.com/refind/)

![rEFInd mountain](https://i.imgur.com/7S32qSm.png)

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/rEFInd-mountain/theme.conf` at the end of
    `refind.conf`.
