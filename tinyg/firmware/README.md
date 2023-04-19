# Usage

1. Ensure the TinyG board is powered on
1. Prepare this command in a terminal, but do not hit **Enter** yet:
   ```
   avrdude -p x192a3 -c avr109 -b 115200 -P /dev/ttyUSB0 -U flash:w:tinyg.hex
   ```
1. Hit "Reset" on the TinyG board and within 3-seconds hit **Enter** on the
   command above
1. Wait until the `Thank You` message at the end of the flash
1. Done!
