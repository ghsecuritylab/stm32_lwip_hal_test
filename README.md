STM32 LWip HAL test app
#stm32 #hal #test

This project probably contain a BUG. 
Compiled fine with GCC (arm-none-eabi-), works normal (only ping, fixed IP address (192.168.3.208)). 
But after flashing ST-Link not connected with message "init mode failed (unable to connect to the target)".
If erase chip (via internal bootloader and stm32flash utility), ST-Link connect OK.
