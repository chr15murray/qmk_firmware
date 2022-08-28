# Quick Reminders

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
qmk compile
```

Run the flash util
```
qmk flash
```

Put the keyboard in flash mode by unplugging and then reconnecting while holding Left CTRL + ESC
