# Stripper Fixes
Bunch of Stripper fixes for server owners. Fixing logic broken that allows these custom maps to be played on dedicated server, proving it can be done. 

## Maps included

### Resident Evil 1 by Roku

Fixed tons of stuff that prevents completing the map on a dedicated server.

**re1m4**
- Removed the horde of tanks spawning when you shoot the giant spider
- Added a ton of slashing melee weapons in wheelcart of the spawn, which any is required to progress the campaign. (A knife is scripted to spawn but sometimes it can glitch)

**re1m5**
- Changed the logic of Bill to check the holdout team, not its model.

**re1m6**
- Changed the logic of the tank to check if it's a Tank, not its model, preventing a softlock if it's changed.
- Changed the logic of the rescue radio to check if it was activated by any survivor, not checking the model of the original 4. Prevents a softlock if any custom model (or L4D1) uses the radio.
- Changed the logic of Bill to check the holdout team, not its model. 