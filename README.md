![License](https://img.shields.io/badge/license-BSD--3-orange) ![Bugs](https://img.shields.io/badge/bugs-0%20open-brightgreen) ![Build](https://img.shields.io/badge/Build-passing-brightgreen?logo=github) [![Members](https://img.shields.io/discord/750034898680807434?label=members&logo=discord&color=7289da)](https://discord.gg/CHZea8zvBG)

# H2 Chooch

Custom multiplayer mod for H1-Mod / Call of Duty: Modern Warfare Remastered.

## Installation Guide

1. Download the mod by cloning the repository with Git LFS enabled, or download and extract the project archive.
2. If you use a normal GitHub source ZIP, verify that `mod.ff` and `mod.pak` are real binary files after extraction.
3. If either file is only a small text pointer, get the real files from a Git LFS checkout or another full mod package before launching the mod.
4. Open your game folder that contains `h1-mod.exe`.
5. Open the `mods` folder inside the game directory. If it does not exist, create it manually.
6. Copy the full mod folder named `h2_chooch` into the `mods` folder.
7. Make sure the final path looks like this:

```text
Call of Duty Modern Warfare Remastered\
  h1-mod.exe
  mods\
    h2_chooch\
      h2_chooch.bat
      info.json
      mod.ff
      mod.pak
```

8. Launch the mod with the included `h2_chooch.bat`, or run the following command from the main game directory:

```bat
h1-mod.exe -multiplayer -mod "mods\h2_chooch"
```

## Notes

- `mod.ff` and `mod.pak` are tracked with Git LFS, so they may be missing from a regular source ZIP.
- If either file opens as a short text pointer instead of a large binary file, download the real assets or copy them from a proper Git LFS checkout.
- The included `h2_chooch.bat` changes into the game directory automatically before launching the mod.

## License

Copyright (c) 2026 Shadow. All Rights Reserved. See [LICENSE](LICENSE).
