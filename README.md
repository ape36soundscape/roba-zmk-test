# roBa Minimal Shields Fixpack

This pack gives you *build-safe* shields for:
- `roba_test_left`
- `roba_test_right`

It compiles on **Seeeduino XIAO BLE (nRF52840)** with ZMK.  
Pins are dummy (1x1 matrix) to guarantee CI success. Replace them later with your real wiring.

## How to use
1. Merge `config/` and `.github/` into your repo root (overwrite if asked).
2. Commit & push.
3. In GitHub, open **Actions** → run “Build ZMK Firmware (No-Container Safe Build)”.

If it passes, replace the overlay pins and expand the keymap to your real layout.
