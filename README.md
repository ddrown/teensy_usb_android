Teensy USB Keyboard/Mouse/Joystick for Android

changes from usb_hid:
  * set_media now takes a keycode from the 0xC (Consumer) page
  * set_media can now send all consumer page (0xC) keys 0x00-0xFF as well as 0x18A, 0x18C, 0x18D, 0x18E, 0x1B7, 0x1BC, 0x221, 0x223
  * there can only be 5 normal keys pressed at a time, instead of 6
