# Miyoo Mini Plus (+) Recommended Overlays + Setup

[/u/1playerinsertcoin](https://www.reddit.com/user/1playerinsertcoin) is the messiah of overlays. I'm just a humble servant spreading the word.

This repository contains a collection of recommended overlays for the Miyoo Mini Plus (+) handheld console. The overlays are designed to be used with the [RetroArch](https://www.retroarch.com/) emulator, which is included with the [Onion](https://onionui.github.io/) operating system.

## Requirements

Onion v4.3.1 or later is required as that's when most Perfect overlays were [added](https://github.com/OnionUI/Onion/pull/1436). I have added newer overlays that are not included in the latest release.

In `Settings` > `Display` be sure to set the following:
  - Lumiance: 07/20
  - Hue: 10/20
  - Saturation: 14/20
  - Contrast: 18/20

Check `root/RetroArch/cpuclock.txt` I went for the safer 1800 but you can try 1900. [Video](https://www.youtube.com/watch?v=2ptdAy3nZ8Y&t=307s) guide for more information on overlclocking.

## Installation

1. [Download](https://download-directory.github.io/?url=https%3A%2F%2Fgithub.com%2FSavageCore%2FMiyooMiniOverlayGuide%2Ftree%2Fmain%2Fmm_plus%2Froot) the `root` directory from this repository.
2. Turn off your device and insert the SD card into your computer or use SFTP/SMB or whatever.
3. Copy the contents of the `root` directory to the root of your SD card. This will add the overlays and filters.
4. Reinsert the SD card into your device and turn it on.
5. Follow all sections below to configure the overlays for each system.

Any items in bold are my personal preferences

### CRT - [Link](https://www.reddit.com/r/MiyooMini/comments/15u78vy/i_made_a_240p_crt_overlay/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Overlay Preset > 4-3 > CRT > Perfect_CRT(read-instructions) > **`Perfect_CRT-240p.cfg`** or `Perfect_CRT.cfg` or `Perfect_CRT-noframe.cfg`

    ℹ️ I use the 240p version for playing Neo Geo games but you can experiment with the other higher res overlays with or without the frame

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > On
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bilinear

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all games of the same system)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

ℹ️ Bonus tip: Under `Quick Menu` > `Core Options` set
  - `CPU Clock` to 200% (Helps with slowdowns in Metal Slug X for example)
  - `DIP Switches` > `Free play` > `On` (No more credits needed in compatible games)

### GB / Game Boy - [Link](https://www.reddit.com/r/MiyooMini/comments/18e2o0z/i_remastered_my_game_boy_dmg_overlay/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Display Overlay > On
  2. Overlay Preset > GB-GBC > Perfect_GB(read-instructions) > `DMG` >  `Perfect_DMG-EX.cfg`

- Go back to `Core Options`

  1. GB Colorization > Custom
  2. Interframe Blending > Simple
  3. Manage Core Options > Save Content Directory Options

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > On
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bilinear

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all GB games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### GBC / Game Boy Color - [Link](https://www.reddit.com/r/MiyooMini/comments/1857xa7/i_made_a_game_boy_color_overlay/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Display Overlay > On
  2. Overlay Preset > GB-GBC > Perfect_GBC(read-instructions) > `Perfect_GBC.cfg`

- Go back to `Core Options`

  1. GB Colorization > GBC
  2. Color Correction > GBC Only
  3. Color Correction Mode > Accurate
  4. Color Correction - Frontlight Position > **`Above Screen`** or `Central`

      ℹ️ Above Screen is lighter, for more realistic GBC colors whereas Central is darker, for more vibrant colors and inky blacks

  5. Interframe Blending > Simple

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > On
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bilinear

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all GBC games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### GBA / Game Boy Advance - [Link](https://www.reddit.com/r/MiyooMini/comments/18ovuld/i_made_a_game_boy_advance_overlay/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Overlay Preset > GBA > Perfect_GBA(read-instructions) > `Perfect_GBA.cfg`

- Go back to `Core Options`

  1. Video > Color Correction > OFF
  2. Video > Interframe Blending > Simple (*Note:* If you don't like the image ghosting, turn it OFF, but you may see flickering elements in games.)

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > On
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bilinear
  3. Video Filter > GBA > Filter for overlays > GBAOffset.filt

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all GBA games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### Game Gear - [Link](https://www.reddit.com/r/MiyooMini/comments/199wwsw/i_made_a_sega_game_gear_overlay/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Display Overlay > On
  2. Overlay Preset > GG > `Perfect_GG.cfg`

- Go back to `Core Options`

  1. Video > LCD Ghosting Filter > Weak
  2. Video > Renderer > Accurate
  3. Manage Core Options > Save Content Directory Options

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > Off
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bilinear

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all GG games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### Mega Drive / Genesis - [Link](https://www.reddit.com/r/MiyooMini/comments/1azsjy8/in_case_you_missed_it_1playerinsertcoin_perfect/ks3lbiz/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Overlay Preset > 4-3 > CRT > Perfect_CRT(read-instructions) > `Perfect_CRT-240p.cfg`

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > Off
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bicubic
  3. Video > Video Filter > Blargg NTSC MD > `Blargg_NTSC_MD_Composite2`

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all MD games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### Neo Geo Pocket / Color by drkhrse - [Link](https://github.com/drkhrse/drkhrse_miyoo_bezels)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Display Overlay > On
  2. Overlay Preset > **`NGPC`** or `NGP` > **`NGPC.cfg`** or `NGP.cfg`

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > On
      - Crop Overscan > Off

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all NGP games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### PICO-8 by /u/ConspiratorGame - [Link](https://www.reddit.com/r/MiyooMini/comments/1cv9n4m/pico_gear_overlay_for_miyoo_mini_plus/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Display Overlay > On
  2. Overlay Preset > `PICO` > `PICO_Gear` > `Scale_(README)` > `Pico_Gear_Scale.cfg`

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > On
      - Keep Aspect Ratio > On
      - Crop Overscan > Off
  2. Video > Video Filter > Pico > `Pico_Gear_Scale_Offset.filt`

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Core Overrides (To use the overlay with all PICO-8 games)
  - Save Content Directory Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.

### SNES / Super Famicom - [Link](https://www.reddit.com/r/MiyooMini/comments/1dlaa4s/i_made_a_snes_crt_overlay/)

- **During a game**: Menu + Select > On-Screen Overlay

  1. Display Overlay > On
  2. Overlay Preset > SFC > `Perfect_CRT(SNES).cfg` or **`Perfect_CRT(SNES-noframe).cfg`**

- Go back to `Settings`

  1. Video > Scaling >
      - Integer Scale > Off
      - Keep Aspect Ratio > Off
      - Crop Overscan > Off
  2. Video > Image Interpolation > Bilinear
  3. Video > Video Filter > Blargg NTSC SNES > `Blargg_Perfect_SNES(brt1).filt` or **`Blargg_Perfect_SNES(brt2).filt`**

    ℹ️ `brt1` is more neutral whilst `brt2`is more contrasty and vibrant

- Go back to `Quick Menu` > Overrides and choose one:

  - Save Content Directory Overrides (To use the overlay with all SNES games)
  - Save Game Overrides (To use the overlay with a single game)

- Go back and `Resume` the game.
