![License](https://img.shields.io/badge/license-All%20Rights%20Reserved-red) ![Bugs](https://img.shields.io/badge/bugs-0%20open-brightgreen) ![Build](https://img.shields.io/badge/Build-passing-brightgreen?logo=github) [![Members](https://img.shields.io/discord/750034898680807434?label=members&logo=discord&color=7289da)](https://discord.gg/CHZea8zvBG)

# H2 Chooch

Custom multi-player mod for H1-Mod / Call of Duty: Modern Warfare Remastered.

## Installation Guide

1. Download the mod from GitHub as a ZIP file, or clone/download it using your preferred method, but do not use the `mod.ff` and `mod.pak` files included in that download.
2. Download [`mod.ff`](ADD_MOD_FF_LINK_HERE) and [`mod.pak`](ADD_MOD_PAK_LINK_HERE) manually if you are using the normal GitHub ZIP download.
3. These two files are hosted through GitHub Large File Storage (Git LFS), which means GitHub may not include the real file contents inside the standard source ZIP archive.
4. Extract all files after the download is complete.
5. Open your game folder that contains `h1-mod.exe`.
6. Open the `mods` folder inside the game directory. If it does not exist, create it manually.
7. Copy the full mod folder named `h2_sireli_p2` into the `mods` folder, and make sure the manually downloaded `mod.ff` and `mod.pak` are placed inside that folder.
8. Make sure the final path looks like this:

```text
Call of Duty Modern Warfare Remastered\
  h1-mod.exe
  mods\
    h2_sireli_p2\
      info.json
      mod.ff
      mod.pak
      maps\
      h1-mod_sireli_p2.bat
```

9. Launch the mod using the following `.bat` file, placed in the main game directory alongside `h1-mod.exe`:

```bat
h1-mod.exe -singleplayer -mod "mods\h2_sireli_p2"
```

## Notes

- `mod.ff` and `mod.pak` are tracked with Git LFS, so they may be missing from a regular source ZIP.
- If either file opens as a short text pointer instead of a large binary file, download the real assets or copy them from a proper Git LFS checkout.
- If you use a `.bat` launcher, it is best to keep it next to `h1-mod.exe` in the main game folder.

## License

This project uses a custom "All Rights Reserved" license. See `LICENSE` for details.
