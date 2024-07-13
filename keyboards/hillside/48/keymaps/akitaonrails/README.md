Upload keymap.json to config.qmk.fm to visually change the layout.

Download the new keymap then run:

    mv ~/Downloads/hillside_48_0_1_akitaonrails-hillside-48.json keyboards/hillside/48/keymaps/akitaonrails/keymap.json

To convert from json to c:

    qmk json2c -o keymap.c ~/Downloads/hillside_48_0_1_akitaonrails-hillside-48.json

Compile with:

    qmk compile -kb hillside/48 -km akitaonrails -e CONVERT_TO=promicro_rp2040


