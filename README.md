# OSUS
### Open Source USB Stack Tester Board

When writing Open Source USB stacks the testing of all different version of mcu's and crystal speeds to make the right #defines and linker maps for the firmwares can be a bit tedious.

OSUS will make life a bit easier by removing most of the parts required on the boards to be tested by moving the other parts to this master board. The test-boards basically only need a decoupling cap two and a 14 pin 0.1" pin header - that's it.

On the OSUS master board there's a Reset button and .a extra button to be used for invoking the bootloader or just for general usage. There are also three status LEDs for simple debugging and a connector to a BusPirate LCD adapter for more involved stuff.

The crystal clock speed can be set in 15 steps between 1.25MHz and 48MHz and is provided to the test-board in both 5 and 3.3 volt versions.

Of course there are a ICSP connector and a USB Mini connector on the board as well. It's possible to disconnect the USB D+/D- by removing two jumpers.

<img src="https://raw.github.com/SmallRoomLabs/OSUS/master/Misc/OsusMaster-annotated.jpg" width="75%" height="75%">
