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
