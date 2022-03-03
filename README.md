# Armachat-circuitpython
New Armachat based on Raspberry Pi PICO an Circuitpython code

**Software working features:**

- send message with header and store to memory
- receive message and parse header, store to memory
- display message memory with message details like SNR and RSSI
- count messages in memory by type
- display some hw details like free memory and power supply voltage, it is good for future battery operation
- Terminal display with messages from background systems
- AES256 encryption
- message confirmation and status change in memory
- boot safe mode


**TODO:**

- Need much better LoRa libray with, CAD, status detection, and INTERUPT !!!
- contact list
- setup and save configuration
- save memory to flash

...

**Kayto Fork Notes**
- experimental comments in code to test writing to text files.
- added additional menu items - currently not developed.
- added cpu temp to information screen
- added a very rudimantary ping command - press 'p' to send a ping message. sends user name to reciever.
