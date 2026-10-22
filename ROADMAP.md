# Rimfrost – Roadmap

Tick items off with `[x]` when they are done. Add new items at the bottom of the right section.

## Done

### Co-op
- [x] Co-op in the overworld (PeerJS, host + guest)
- [x] Co-op in dungeons: shared instance, same seed and levels for everyone
- [x] Monsters in dungeons are shared between players (the host runs them)
- [x] Levers, runes and gates are synced between players
- [x] Shared kills, XP and loot inside dungeons
- [x] A new player joins an ongoing dungeon instead of resetting it
- [x] Co-op in dungeons tested with a friend and working

### Developer tools
- [x] Dev panel (`?dev` in the address, the DEV button or the key below Esc)
- [x] Set level, gold, heal, god mode, teleport, enter dungeon, give items
- [x] Balance test with a bot (1 monster, 3 monsters, elite) and saved results
- [x] Balance test supports Druid forms (caster, bear, wolf)

### Class balance
- [x] Mana: all costs ×0.5
- [x] All player damage ×0.8
- [x] Damage modifier per class (Mage 1.15, Warrior 1.15, Druid 1.10, Paladin 0.70)
- [x] Warrior armor 0.85 → 0.80
- [x] Druid bear form armor 0.6 → 0.7
- [x] Class roles decided (see below)

### Hunter pets
- [x] Hunter pets (Bear level 5 tank, Wolf level 10 DPS): tested and balanced with the dev test

### World
- [x] Line of sight based on terrain: mountains, cliffs, walls, houses, gates, ice walls and big rocks block attacks, spells, heals and monster aggro (trees, water and lava do not)

**Roles:** Paladin very good solo · Warrior good solo (tank) · Druid medium–good · Hunter medium · Mage hard solo but very good in a group · Priest medium–hard solo but essential in a group

## In progress

- [ ] Pets in co-op: built, needs testing with a friend

## Planned

- [ ] New equipment and new sprites (paused for now)
- [ ] Rebalance after bigger changes (run the dev test again)
- [ ] Test the classes in a group (roles in co-op, not only solo)

### Changes
- [ ] Bigger starting areas, with level 1–2, 3–4 and 4–5 enemies kept in their own parts of the zone instead of mixed together (hard for new characters)
- [ ] Rewrite the Wing Clip description, and review the descriptions of all skills
- [ ] Better UI on mobile

### Additions
- [ ] Bigger world map with more areas
- [ ] Water only in specific water areas (lakes, rivers), no random water tiles
- [ ] Trading between players in co-op (items, gear and gold)

## Ideas to investigate

- [ ] More dungeons or difficulty levels
- [ ] Better crit balance (big attacks can kill a monster in one hit)
- [ ] Mage-specific mana management (its own identity)

## Known issues

- [ ] A guest who connects while in a dungeon is sent out of it (on purpose, but could be smoother)
- [ ] The dungeon stops if the host closes the game
