# Zandronum - Revival

Revive your survival team mates by picking up keys!

## Description

"Revival" is an extremely simple modifier for the Survival mode in [Zandronum](https://zandronum.com).\
Any player who has died in the current round will be revived when a living player picks up a key.

## Installation

### Via release
1. [Download](https://github.com/Hezkore/zandronum-revival/releases) and place `revival.wad` to your Zandronum directory
1. Load the mod using the `-file revival.wad` command line argument
2. Play Survival like normal

### From source
1. Clone repo `git clone https://github.com/Hezkore/zandronum-revival.git`
2. Compile `SURVREV.txt` into `SURVREV.o` using [ACC](https://www.zdoom.org/downloads)
3. Create `revival.wad` WAD with [SLADE](https://slade.mancubus.net)
4. Place `SURVREV.o` and `LOADACS.txt` in WAD

## Things to improve

The instant revival can be jarring.\
A message should appear on each dead player's screen with a countdown and sound before they are revived.

An option for adjusting the countdown time could also be added.\
At the end of the countdown, it could check if at least one player is still alive.\
This would prevent a player from rushing to pick up a key to revive any dead players and then dying themselves.