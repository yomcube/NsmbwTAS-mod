# NsmbwTAS-mod
A mod of New Super Mario Bros Wii to help with TASing!

# Setup
Download the latest release. It comes as a riivolution patch. On newer dolphin versions, you can simply start the game with the riivolution patch active. On older version of Dolphin, you'll have to use [this tool](https://github.com/Asu-chan/RiivolutionIsoBuilder/releases/tag/v1.0) to create an iso with it and your copy of the game.

This mod is best used with the [TAS Studio setup](https://github.com/MGR-tas/nsmbwTAStudio), so that you can easily move TASes to and from the TAS Mod and the normal game.

As a fair warning, loading times will be different on the TAS Mod than they are in the normal game. So be wary of enemy dances or other music cycles causing desyncs.

# Controls
- Toggle hitboxes: Hold Jump + Press Minus
  - if using TAS Studio, you can use the command `HitboxMode, [0-2]` to change the hitbox mode.
  - 0 = none, 1 = basic, 2 = advanced. In-game hotkey only toggles 0 and 1.
- Toggle Input Display: Hold Run + Press Minus
  - if using TAS Studio, you can use the command `InputDisplay, [0-1]` to toggle the input display.
- Toggle Grid: Hold Up + Press Minus
  - if using TAS Studio, you can use the command `Grid, [0-1]` to toggle the grid.
- Cycle Entity Info Display: Hold Down + Press Minus
  - if using TAS Studio, you can use the command `InfoDisplay, [0-2]` to change the info display mode.
  - 0 = none, 1 = speed, 2 = position

# Source Info
This mod is built off of [NSMBWer+](https://github.com/Developers-Collective/NSMBWerPlus/tree/vanilla-compatible). For information on building the code, read the ReadMe file in that repository.