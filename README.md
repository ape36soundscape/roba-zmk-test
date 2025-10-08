# roBa ZMK Test Firmware

This repository builds ZMK firmware for the **roBa** keyboard,
based on **kumakey’s original design**, and now adapted for the latest
ZMK mouse input support.

---

## Features

- ✅ ZMK 3.x compatible  
- ✅ Seeeduino XIAO BLE support  
- ✅ PMW3610 optical sensor via [badjeff/zmk-pmw3610-driver](https://github.com/badjeff/zmk-pmw3610-driver)  
- ✅ Input handled by ZMK’s new input-processors layer  
- ✅ Dual-side (Left / Right) build with UF2 outputs  

---

## Credits

This work builds on the efforts of:

- **kumakey** — roBa / mona hardware design  
- **badjeff** — PMW3610 driver integration  
- **ZMK team** — official firmware base and mouse input support  

Thank you to everyone who contributed to the open-source keyboard ecosystem.

---

### Build Instructions

1. Fork this repository:  
   https://github.com/ape36soundscape/roba-zmk-test

2. Go to **Actions → Build ZMK Firmware → Run workflow**

3. After build, download:
