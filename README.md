# rEFInd-mountain

A clean mountain theme for the [rEFInd UEFI boot manager.](http://www.rodsbooks.com/refind/)

<<<<<<< HEAD
<<<<<<< HEAD
![rEFInd mountain](https://i.imgur.com/Ra7q34i.png)
=======
![rEFInd mountain](https://i.imgur.com/4TjImbH.png)
>>>>>>> 94d8ddf448b19843a7e89518a42effb1fb1236df
=======
![rEFInd mountain](https://i.imgur.com/4TjImbH.png)
>>>>>>> 94d8ddf448b19843a7e89518a42effb1fb1236df

### Usage

 1. Locate your refind EFI directory. This is commonly `/boot/EFI/refind`
    though it will depend on where you mount your ESP and where rEFInd is
    installed. `fdisk -l` and `mount` may help.

 2. Create a folder called `themes` inside it, if it doesn't already exist

 3. Clone this repository into the `themes` directory.

 4. To enable the theme add `include themes/rEFInd-mountain/theme.conf` at the end of
    `refind.conf`.
    