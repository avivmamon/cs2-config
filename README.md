# Counter Strike 2 - Config

This repository contains custom configuration files for Counter-Strike 2. These include an `autoexec.cfg` for general gameplay tweaks and a `training.cfg` for practice mode settings.

## Installation

1. Download both `autoexec.cfg` and `training.cfg`.
2. Place these files in the following directory:
    ```
    C:\Program Files (x86)\Steam\steamapps\common\Counter-Strike Global Offensive\game\csgo\cfg\
    ```
   
## Launch Options

To maximize the potential of these configurations, set your CS:GO launch options to:
```
-dev -novid -freq 144 -refresh 144 -tickrate 128 -maxplayers_override 50 -nojoy -d3d9ex +exec autoexec -tickrate 128 -netconport 21222
```

### autoexec.cfg
Covers a range of tweaks from network and audio to mouse settings.  
#### Button Binds

##### Weapon Binds:
- Numpad 8: Buy Revolver (`buy_revolver`)
- Numpad 5: Buy MAC-10 (`buy_mac10`)
- Numpad 2: Buy Scout (`buy_scout`)
- Numpad 1: Buy Duellies (`buy_duellies`)
- Numpad 3: Buy XM (`buy_xm`)
- Numpad 4: Buy Galil (`buy_galil`)
- Numpad 6: Buy P90 (`buy_p90`)
- Numpad 7: Buy AWP (`buy_awp`)
- Numpad 9: Buy AK/M4 (`buy_akm4`)

##### Grenade Binds:
- X: Quick HE Grenade (`slot3;buy hegrenade;slot6;`)
- Numpad Enter: Quick HE Grenade (`slot3;buy hegrenade;slot6;`)
- C: Quick Molotov (`slot3;buy incgrenade; slot10;`)
- Numpad Plus: Buy Incendiary (`buy incgrenade`)
- Mouse 4: Quick Smoke Grenade (`slot3;buy smokegrenade;slot8`)
- Mouse 5: Quick Flashbang (`slot3;buy flashbang;slot7`)

##### Misc Binds:
- Delete: Reload Config (`exec autoexec; say Config reloaded; echo Config reloaded`)
- Page Up: Execute Training Config (`exec training`)


### training.cfg
Optimized for practice mode, includes cheats and visual aids.

To use in practice server, type `exec training` in the console.
