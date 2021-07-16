# Among Us mod for Doom 2
## Prerequisites
- doom2.wad
- Zandronum - https://zandronum.com/
  - may run in other applications, only tested with Zandronum

## Change log
### v1.1 - 2021.07.01 
#### menu
- added sounds and cursors
#### map
- fixed reactor texture missing / blocking
- fixed storage barrel texture alignment
- "Fix Lights" now requires 5 switches to be up
- sped up light change during fixing / dimming lights
  - plus/minus 5 every 2 tics -> plus/minus 20 every 2 tics
- updated music to be ship ambiance
- pickups replaced with randomized item boxes
  - weapons: yellow
  - ammo: brown
  - blue: inventory items
  - rainbow: powerups
- medbay scan
  - decreased healing time, 40 tics -> 35 tics
  - increased healing ammount, 5 -> 8
  - added healing sound
#### weapons
- removed bfg10k
  - way too over powered, will add it back when nerfed
- decreased weapon switching duration by half
- black hole generator
  - sped up firing rate
- sniper rifle
  - changed zooming, 6x and 12x -> 2x and 10x
- m6d pistol
  - added scoped hud sprite
  - updated firing sound
  - added scope sound
- fist
  - increased range, 64 -> 96
  - updated punch sound
- pistol
  - updated firing sound
#### powerups
- added
  - Speedster: 1.5x movement for 45 seconds
  - MegaHeal: Full health
  - Rapid Fire: Double weapon firing speed for 30 seconds
  - Double Damage: Increases player attack streangth by 2 for 30 seconds
  - Protection: Decrease damage taken by half for 30 seconds
- updated
  - partial invisibility: player is 90% transparent
#### inventory
- added
  - Chickenator: turn players into chickens (ArtiEgg from Heretic)

### v1.0 - 2021.06.25
- created new map of The Skeld (map01)
- created new player class
- added 4 new weapons
  - M6D Halo Pistol
  - Sniper Rifle
  - Black Hole Generator
  - BFG 10K

## Credits
### Among Us
- Home page: https://innersloth.com/gameAmongUs.php
- Any textures/graphics/sprites/sounds from the Among Us game are owned by Innersloth

## Weapons
### BFG10K
- Class: 7
- Type: Hitscan
- Palette: Doom
- Summon: STBFG10K
- Ammo Type: Cell
- Altfire: No
- Powered Mode: No
- Brightmaps: No
- Actor modification: No
- ACS: No
- Code: The Skulltag Team, Ghastly (ZScript conversion)
- GLDefs: The Skulltag Team
- Sounds: The Skulltag Team
- Sprites: Eriance
- Idea Base: Quake 3's BFG10k

### Black Hole Generator
- Class: 7
- Type: Projectile
- Palette: Custom
- Summon: BHGen
- Ammo Type: Cell
- Altfire: No
- Submitted: Gothic
- Decorate: Gothic
- GLDefs: Gothic
- Sounds: Raven Software (Quake 4), Epic Games (UT 2004)
- Sprites: NMN, Zero Prophet, Reactor, Kronos, Midway
- Sprite Edit: Gothic
- Idea Base: Dark Matter Gun from Quake 4, Borsch from Russian Overkill

### Sniper Rifle
- Name: M40A1
- Class: 6
- Type: Hitscan
- Palette: Custom
- Summon: M40Rifle
- Ammo Type: M40762Ammo
- Altfire: Yes
- Powered Mode: No
- Added States: No
- Submitted: TODM
- Decorate: TODM
- Sounds: VALVe
- Sprites: HL:OpFor, TODM
- Sprite Edit: Cory Whittle, TheDarkArchon, TODM
- Idea Base: Left 4 Dead 2/CS:S/HL:OpFor "AWP"

## Decorations
### trees
- Name: Garden Plantations
- Connection: None
- Palette: Doom
- Summon: Gardentree[1-2], Gardenbush[1-3]
- Ambient Sound: N/A 
- De-/Activatable: N/A
- Destroyable: Yes
- Special Effects: N/A
- ACS: N/A
- Submitted: Yuyu3
- Decorate: Yuyu3
- Sprites: Rogue Entertainment, Raven Software
- Sprite Edit: Yuyu3
- Idea Base: Need to Vitalize doom Dry Trees
