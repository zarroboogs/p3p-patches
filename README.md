
# P3P Patches

![mod](https://cdn.discordapp.com/attachments/546718581572894730/976179261578809404/mod.gif)

## Usage

1. To install:
   - On PPSSPP, place `ULUS10512.ini` in `ms0:/PSP/Cheats/`. If the file already exists, add the contents of the provided `ULUS10512.ini` file to it.
   - On PSP, install CWCheat and add the contents of `ULUS10512.ini` to `ms0:/seplugins/cwcheats/cheats.db`.
2. Enable the patches you'd like to use via the cheats menu.

## Patches

For ULUS10512 (US) v1.00

- *Intro Skip* - Skips logos and intro movie when booting the game.

- *Mod Support* - File replacement via (listed from highest to lowest load priority):

  1. Loose files in `ms0:/PSP/P3P/bind/`
  2. `ms0:/PSP/P3P/mod.cpk`
  3. `ms0:/PSP/P3P/mod1.cpk`
  4. `ms0:/PSP/P3P/mod2.cpk`
  5. `ms0:/PSP/P3P/mod3.cpk`

  Make sure to **disable the Data Install setting** via the Config menu as files from installed data will override some game files (even if they were replaced via a mod).

  Loose file loading is done via a leftover debug function and might be unstable.
