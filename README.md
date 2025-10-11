# Auto-build workflow for ZMK (all shields)

This workflow **auto-discovers every shield** under `config/boards/shields/*/zmk.yml`,
reads its `id`, and builds firmware for all of them on **Ubuntu (no Docker)**.

## How to install
1. Drop `.github/workflows/build.yml` into your repo (overwrite if asked).
2. Commit & push to `main` (or run manually in GitHub → Actions).

## Requirements
- Each shield must have: `config/boards/shields/<name>/zmk.yml` with `id: <name>`
- Optional but recommended: `<name>.overlay`, `<name>.keymap`

## Change board
If you are not using **Seeeduino XIAO BLE**, edit the `BOARD` env at the top:
```
env:
  BOARD: <your_board_here>
```
