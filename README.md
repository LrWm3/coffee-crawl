# Coffee Crawl fork

Crawl is won by lair. Therefor, coffee crawl is the first ten floors of crawl, then one floor of Zot.

The goal of this game is to make a 15-30 minute crawl.

## Upcoming changes

Core changes

- [x] remove lair, orc, vaults, depths
- [x] shorten dungeon to 10 levels
- [x] temple always appears on level 2
- [x] remove portal branches besides bazaar
- [x] actually remove depths
- [x] remove drop restrictions for D1 to D4 to avoid too many 'boring' floors
- [x] remove things like adders from D:10 since the game is almost over by D:10
- [x] map zot enemies to dungeon enemies in random gen (for now)
- [x] remove abyss access via banish
- [x] remove abyss access via distortion weapons
- [x] remove abyss access via starting role
- [x] remove abyss access via god abilty
- [x] remove abyss access via distortion unwielding, replace with maligned_gateway
- [x] remove abyss access via Zot trap, replace with maligned_gateway
- [x] remove abyss access via miscast, replace with maligned_gateway
- [x] revert mapping zot enemies to dungeon enemies
- [x] rebalance zot enemies for a 10 level crawl
- [x] remove orb run
- [x] end the game when the player exits the realm of zot with the orb

## Clean up changes

Changes to clean up the experience.

- [ ] no more id-minigame items such as potion of degeneration or scroll of torment, amulet of inaccuracy
- [ ] remove curse mechanics outside of Ashenzari
- [ ] set all items to 'known' on game start
- [ ] spell-book crash when I press '\'
- [ ] generating dungeon should only say 'generating zot'

## Core improvements v2

- [ ] figure out what to do about skills and exp

## Extended changes

Changes I would like to try, ala hellcrawl.

- [ ] remove resistances
- [ ] shorten the game to 6-8 levels
- [ ] display damage in messages
- [ ] monsters have fixed hp
- [ ] remove dexterity
- [ ] remove bows
- [ ] remove upstairs
- [ ] remove food
- [ ] remove strength and intelligence
- [x] remove id minigame
- [x] remove id scrolls (v1)
- [ ] smooth progression
- [ ] add in monsters from other floors
- [ ] run crawl server with this version
- [ ] stealing the orb to increase the players durability and skill-levels

## Bad ideas

Changes I would like to try which are probably bad ideas.

- [ ] give every enemy in the game the briar patch ability thorn hunters have to prevent luring
- [ ] either flat increase piety gain or decrease piety cap

## Stolen Ideas

Ideas which could be taken from other forks.

- [food reform](https://github.com/Hellmonk/hellcrawl/commits/master?after=f897f43cf01d0610cee5576fc3d3daf99aa08de5+489)
- [ammoless](https://github.com/Hellmonk/hellcrawl/commits/master?after=f897f43cf01d0610cee5576fc3d3daf99aa08de5+209)
- [anti-scumming clock](https://github.com/Hellmonk/hellcrawl/commit/0d3c2767a36dc7e84febad25f076c201fdb97b71)
- [corpseless](https://github.com/Hellmonk/hellcrawl/commit/d933a39257244af08d6ced9b720772819bf01815)

## References

[DCSS README](https://github.com/crawl/crawl)
[Dungeon Crawl Short Soup](https://github.com/dcandido/crawl)
