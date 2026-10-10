# Sekiro in Gotham

A UE4SS Lua mod for **Batman: Arkham Knight** that aims to bring Sekiro-style combat
(katana, deflect/parry system) into Gotham.

> **Status: early work in progress.** Right now the mod only loads and registers an F9 keybind
> that prints a message. The katana and deflect system are not implemented yet.

## Install
1. Install Batman: Arkham Knight (PC).
2. Copy the contents of this repo into the game's `Binaries/Win64/` folder
   (so `ue4ss.dll`, `UE4SS-settings.ini` and `Mods/SekiroInGotham` sit next to the game exe).
3. Launch the game. The UE4SS console should show `[SekiroInGotham] Mod loaded`.

## Roadmap
- [ ] Katana weapon swap
- [ ] Sekiro-style deflect / parry
- [ ] Posture meter

## Credits
- [UE4SS](https://github.com/UE4SS/RE-UE4SS) (`ue4ss.dll`, `UE4SS-settings.ini`) is third-party and
  distributed under its own license (MIT). Consider linking to the official release instead of bundling it.

## Disclaimer
Fan project, not affiliated with or endorsed by Warner Bros., Rocksteady, FromSoftware or Activision.
Contains no game assets; you need your own copy of the game. Sekiro and Batman are trademarks of their owners.
