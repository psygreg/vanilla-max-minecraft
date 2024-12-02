## Changelog

### Added

- Distant Horizons (optional - see developer notes)
- Better Sniffers
- Cheaper Templates

### Removed

- Better End Cities Vanilla (redundant)
- 1.21.2 Bundle Recipe Backport (redundant)

### Adjusted

- Iris (shaders) is now optional 
- Visuality (particle effects) is now optional
- Shoulder Surfing Reloaded (enhanced 3rd person mode) is now optional
- Default modpack (no optionals enabled) now requires 3GB of RAM (previously 4GB)
**Optional mods can be enabled in the mod list.**
- Foals can never get worse stats than its parents
- Horse stepheight increased by 10%
- Saddled Horses, Donkeys and Mules no longer wander away
- Horses, Donkeys and Mules can now be ridden through portals
- Visibility while mounted improved
- Mounting animals now 'fade out' when looking down allowing you to see what's below

### Fixed

- Mounting animals on stairs no longer causes rubberbanding

### Developer Notes

I was able to improve the implementation of Distant Horizons to a point it works reasonably well without stuttering, however, I do not recommend using it unless you have at least an Intel Core i7 12th generation or Ryzen 7 5th generation or more recent. It dramatically increases CPU usage.

After thoroughly testing the modpack without certain visual improvements, and making sure taking those away won't make the experience any worse, I've decided to ship the modpack from now on with those visual improvements disabled by default, in order to make it playable for most PCs. 

Carts were a good addition, but they weren't enough to make horse riding more compelling. Those changes tackle that by making the experience smoother and horse breeding more straightforward.

Sniffers have received some attention as well, with a better loot table to their sniffing, and spawn naturally on villages - as many people never got to see one. 

Templates were made cheaper to better represent the place of Netherite gear in the modpack as no longer the endgame, but a late game set. 
