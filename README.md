# BootROM Dumper

What to know about the Bootrom Dumper Utility (BDU) :
- you need a mac or linux box to use it / build it
- libusb > 1.0.8 required
- execute it with root privileges (sudo ./bdu)
- by default compatible only with A4 devices : (iPhone 4, iPod 4G, iPad, AppleTV 2)
     it's possible to extend the compatibility to older devices as well (iPhone 3Gs, iPod 3G) by changing:
        * the offset to the call of usb_wait_for_image in payload.S
        * exploit offsets in bdu.c
     was too lazy to automate this stuff...

Happy Reverse Code Engeneering !

~ pod2g
