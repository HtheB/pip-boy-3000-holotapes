# Brick Bounce Source

This folder contains the editable source for the Brick Bounce game pages. The
readable application launcher is `../app.js`.

- `MAIN.JS` contains the title screen and main menu.
- The remaining `.JS` files are game pages and helpers.
- `LEVELS.TXT` contains the editable 50-level layout data.

The matching runtime files live in `../assets/`. The runtime JavaScript is
pretokenized for Espruino and must be copied as binary data; opening and
re-saving it as text can corrupt the holotape.
