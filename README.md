# lily58 keymap

place in `$HOME/qmk_firmware/keyboards/lily58/keymaps`

### Flashing

this layout uses `EE_HAND`
`qmk flash -kb lily58 -km lzl-lily58 -bl avrdude-split-left`
`qmk flash -kb lily58 -km lzl-lily58 -bl avrdude-split-right`

### Font

the font is located in `font.c`

a new logo can be generated editing the `./assets/alc_font.png`
and generating a new `font.c` file with `https://joric.github.io/qle/`

more info located in `https://docs.qmk.fm/features/oled_driver#logo-example`
