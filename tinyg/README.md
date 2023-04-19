# Usage
To "set" the configuration from the file, use:
```bash
$ stty -F /dev/ttyUSB0 115200 -parity cs8 -cstopb
$ cat tinyg-settings.conf > /dev/ttyUSB0
```
