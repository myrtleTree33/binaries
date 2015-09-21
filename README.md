# Binaries
This is a temporary distribution vehicle for EARLY tests of the Espruino ESP8266 port.

The command to flash the device is:

    esptool --port COM18 --baud 115200 write_flash  --flash_freq 40m --flash_mode qio --flash_size 4m 0x00000 ESP8266_0x00000.bin 0x10000 ESP8266_0x10000.bin

Make sure to change the COM port to match your own.

