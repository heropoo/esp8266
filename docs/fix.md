Deploying to ESP8266 with Arduino IDE on MacOS error: “pyserial or esptool directories not found next to this upload.py tool”

Edit `~/Library/Arduino15/packages/esp8266/hardware/esp8266/2.7.4/tools/pyserial/serial/tools/list_ports_osx.py`

Comment out lines 29 and 30 and append these lines:
```
iokit = ctypes.cdll.LoadLibrary('/System/Library/Frameworks/IOKit.framework/IOKit')
cf = ctypes.cdll.LoadLibrary('/System/Library/Frameworks/CoreFoundation.framework/CoreFoundation')
```