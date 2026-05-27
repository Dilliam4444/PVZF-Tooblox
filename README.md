# PVZF Menu

A MelonLoader mod menu for **PVZ Fusion v3.6.1**.

PVZF Menu adds a keyboard-controlled in-game mod menu with player, plant, zombie, world, QOL, unlock, debug, settings, and credits tabs.

> Current version: **v1.1.1**

---

## Features

### Player

- Infinite Sun
- Set Sun amount
- Infinite Money
- Set Money amount
- Pause game
- Unpause game
- Adjustable game speed

### Plants

- Free Seeds
- Fast Recharge
- Cards Always Available
- No Use Limit
- Reset Card Used Times
- Refresh All Cards
- Show Plant Health
- Heal All Plants
- Remove Plant Cooldowns

### Zombies

- Kill All Zombies
- Freeze Zombies
- Slow Zombies
- Weak Zombies
- Damage All Zombies
- Delete Zombie Objects
- Zombie ID selector
- Log Zombies

### World

- Win Level attempt
- Clear Level attempt
- Spawn Sun Burst
- Create Solar
- Create Lunar
- Add Light Level
- Speed Hack
- Game speed controls
- Reset Time Scale

### QOL

- Auto Collect
- Collect Items Once
- Hide UI attempt
- Show UI attempt
- Disable Falling Sun Timer attempt
- Max Card Count attempt
- Happy Random Card attempt
- Log Coins / Suns
- Clean Projectiles
- Low Lag Mode

### Unlocks

- Plant ID selector
- Unlock Selected Plant attempt
- Unlock First 50 Plants attempt
- Unlock First 100 Plants attempt
- Unlock Plant Cards 0–150 attempt
- Log Plant / Card Unlock Methods

### Debug

- Log Board
- Log Cards
- Log Plants
- Log Zombies
- Log Mouse
- Log CreatePlant Objects
- Log Unlock Objects
- Dump GameObjects
- Log Components

### Settings

- Rebind Menu key
- Rebind Pause key
- Rebind Unpause key
- Rebind Infinite Sun key
- Rebind Free Seeds key
- Rebind Fast Recharge key
- Restore Time Scale
- Restore Seed Costs
- Restore Recharge
- Turn All Toggles OFF

### Credits

- Credits tab
- Permanent top-right watermark

---

## Installation

1. Install **MelonLoader** for PVZ Fusion.
2. Build or download `PVZFMenu.dll`.
3. Place the DLL into the game Mods folder:

```text
Game Files/Mods/PVZFMenu.dll
```

4. Launch PVZ Fusion.
5. Press `F6` to open or close the menu.

---

## Game Folder Example

The game folder should look similar to this:

```text
Game Files/
├─ PlantsVsZombiesRH.exe
├─ UnityPlayer.dll
├─ GameAssembly.dll
├─ MelonLoader/
├─ Mods/
│  └─ PVZFMenu.dll
├─ Plugins/
└─ UserData/
```

---

## Default Controls

```text
F6  = Open / Close Menu
F7  = Pause
F8  = Unpause
F9  = Toggle Infinite Sun
F10 = Toggle Free Seeds
F11 = Toggle Fast Recharge

Left Arrow / Right Arrow = Change tabs
Up Arrow / Down Arrow    = Move through options
Enter                    = Select option
```

Controls can be changed in the **Settings** tab.

---

## Build Information

Project setup:

```text
Project type: C# Class Library
Framework: .NET 6.0
Mod loader: MelonLoader
Game type: Unity IL2CPP
Namespace: PVZFMenu
Main file: Main.cs
```

Important references may include:

```text
MelonLoader.dll
UnityEngine.dll
UnityEngine.CoreModule.dll
UnityEngine.InputLegacyModule.dll
UnityEngine.IMGUIModule.dll
Il2Cppmscorlib.dll
Il2CppSystem.dll
Il2CppSystem.Core.dll
Il2Cpp__Generated.dll
Il2CppInterop.Runtime.dll
```

---

## Notes

Some options are experimental because PVZ Fusion uses internal IL2CPP game methods and fields. Features may depend on the current level, game mode, or how the game exposes objects at runtime.

The most reliable features are:

- Infinite Sun
- Set Sun
- Free Seeds
- Fast Recharge
- Cards Always Available
- Pause / Unpause
- Game Speed
- Debug logging

The following features are more experimental:

- Win Level
- Unlock Plants
- Hide / Show UI
- Max Card Count
- Happy Random Card
- Clean Projectiles
- Some zombie control options

---

## Column Planting

Column Planting has been removed from v1.1.1.

It is planned for a future update once the game’s real planting and fusion behaviour is mapped properly.

---

## Version History

### v1.1.1

- Added Credits tab
- Added permanent top-right watermark
- Removed Column Planting from the current build
- Fixed GUIStyle compile issues
- Fixed Canvas compile issue
- Kept keyboard-controlled menu support
- Kept multiple mod categories

### v1.1.0

- Added larger feature set across categories
- Added Unlocks tab
- Added more debug tools
- Added settings and keybind options

### v1.0.0

- Initial working menu base
- Infinite Sun
- Set Sun
- Free Seeds
- Fast Recharge
- Keyboard-controlled menu

---

## Credits

Created by **Seagull**.

Built for **PVZ Fusion v3.6.1** using **MelonLoader IL2CPP**.

Special thanks to:

- PVZ Fusion Translator team
- Blooms QOL
- Lukas for testing

---

## Disclaimer

This is an unofficial fan-made mod menu.

Use at your own risk. Make backups before modifying game files.
