# Quick Reminders

Tweeks:
- Bottom left and top left keys to trigger reset / bootloader (e.g. CTRL+ESC)
- Home Row Mods: 
- Caps Lock as escape
- 

## Existing Config
```
qmk config
# multibuild.keymap=default
# user.keyboard=gmmk/pro/iso
# user.keymap=chr15murray
```

Edit the keymap here:
```
vim keyboards/gmmk/pro/iso/keymaps/chr15murray/keymap.c
```

Build the firmware
```
qmk compile -kb gmmk/pro/iso -km chr15murray

qmk compile -kb keychron/q11/iso_encoder -km chr15murray
```

Run the flash util
```
qmk compile -kb gmmk/pro/iso -km chr15murray

qmk compile -kb keychron/q11/iso_encoder -km chr15murray

```

Put the keyboard in flash mode by unplugging and then reconnecting while holding Left CTRL + ESC
