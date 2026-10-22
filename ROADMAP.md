# Rimfrost – Roadmap

Tick items off with `[x]` when they are done. Add new items at the bottom of the right section.

## Done

### Co-op
- [x] Co-op in the overworld (PeerJS, host + guest)
- [x] Co-op in dungeons: shared instance, same seed and layout for everyone
- [x] Dungeon monsters are shared between players (the host runs them)
- [x] Levers, runes and gates are synced between players
- [x] Shared kills, XP and loot inside dungeons
- [x] A new player joins a running dungeon instead of resetting it
- [x] Dungeon co-op tested with a friend and working

### Dev tools
- [x] Dev panel (`?dev` in the URL, the DEV button or the key under Esc)
- [x] Set level, gold, heal, god mode, teleport, enter dungeon, give item
- [x] Balance test with a bot (1 monster, 3 monsters, elite) and saved results
- [x] Balance test supports Druid forms (caster, bear, wolf)

### Class balance
- [x] Mana: all costs ×0.5
- [x] All player damage ×0.8
- [x] Per-class damage multipliers (Mage 1.15, Warrior 1.15, Druid 1.10, Paladin 0.70)
- [x] Warrior armor 0.85 → 0.80
- [x] Druid bear form armor 0.6 → 0.7
- [x] Class roles decided (see below)

**Roles:** Paladin very good solo · Warrior good solo (tank) · Druid medium–good · Hunter medium · Mage hard solo but very good in a group · Priest medium–hard solo but indispensable in a group

### Hunter
- [x] Hunter shots have a minimum range (70 px); casts are cancelled if the enemy gets too close
- [x] Melee options for Hunter: Raptor Strike, Wing Clip (slow) and melee auto-attack when too close
- [x] Pet bar button (attack / recall, key F) and Dismiss Pet
- [x] Pets in co-op: pets, aggro, Growl/Sweep/Claw and damage numbers synced, tested with a friend
- [x] Friends' spells and arrows are visible in co-op

### Stats and items
- [x] Primary stats Stamina, Intellect, Strength, Agility (Agility = Hunter attack power) with attack crit / spell crit split
- [x] New item generator: stat budget from quality, item level and slot; stats chosen by class
- [ ] Rebalance with the dev test (all classes + Hunter pets) now that gear gives primary stats
- [x] Old items are retired when a character loads

### World
- [x] World is 2× bigger in each direction (same zones and layout, longer travel, same number of mobs spread out)
- [x] Merchants in the 5 small camps (basic potions, buys junk)
- [x] World map can be zoomed and dragged (buttons, scroll wheel, drag)
- [x] Player and NPC models drawn smaller (80 %) to fit better next to the mobs
- [ ] Check the bigger world: gathering nodes were doubled, quest item counts are unchanged

### Interface
- [x] Second action bar (Shift+1–0)
- [x] Map opens by clicking the minimap
- [x] Spellbook lists abilities in the order they are learned

## Planned

- [ ] Hunter pets (Bear lvl 5 tank, Wolf lvl 10 dps): playable, still to do: re-run the L30 balance test (bear/wolf)
- [ ] Change how mobs spawn around the starting area (for example, the closest ones should be a bit lower level)
- [ ] Add more quests per level
- [ ] Rewrite spell descriptions and other in-game text to sound more professional
- [ ] Fix the mobile UI so it matches all current settings (joystick, buttons, second action bar, pet button)
- [ ] New equipment and new sprites (paused for now)
- [ ] Rebalance after bigger changes (run the dev test again)
- [ ] Test the classes in a group (roles in co-op, not only solo)

## Ideas to look into

- [ ] More dungeons or difficulty levels
- [ ] Better crit balance (big attacks can kill a monster in one hit)
- [ ] Mage-specific mana management (its own identity)

## Known issues

- [ ] A guest who connects while inside a dungeon is moved out of it (intended, but could be smoother)
- [ ] The dungeon stops if the host closes the game
