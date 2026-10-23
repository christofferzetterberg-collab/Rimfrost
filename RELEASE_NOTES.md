<!-- For the maintainer: the character select screen shows the three newest sections of this file. Keep the heading format "## vX.Y.Z – date", "### Added/Changed/Fixed" headings and "- " bullets. Only write what a player needs to know. -->
# Rimfrost – Release notes

Newest version first.

## v0.8.0 – 2026-10-23
### Changed
- **Zoom:** the game is drawn 50 % closer than before.
- **Dying in a dungeon:** releasing your spirit now puts you at the nearest graveyard (the closest town or camp). You have to run back to the dungeon entrance to reach your body. The dungeon keeps its progress.

### Fixed
- **Health and mana are saved.** Logging out and back in no longer refills them. You regenerate for the time you were away.
- **Monsters and nodes are no longer respawned when you log out and back in.** Dead monsters and picked nodes keep their respawn timers, which also keep counting while you are away. A page refresh still resets the world.

## v0.7.0 – 2026-10-23
### Added
- Release notes can now be read on the character select screen (the three latest releases).

## v0.6.1 – 2026-10-23
### Added
- The game version is shown on the character select screen and at the bottom of the Esc menu.

## v0.6.0 – 2026-10-23
### Fixed
- **Water:** ponds and lakes are now large, connected areas. The random single water tiles in Silver Grove, the swamp and Bonefields are gone.
- **Entangling Roots:** now has a 20 second cooldown, so enemies can no longer be held in place forever.
- **Humanoid monsters** (Lost Druids, bandits, thieves, ghouls and similar) are drawn at the same smaller size as player characters, so they no longer tower over you.
- **Dying in a dungeon:** releasing your spirit can no longer get stuck.
- **Dungeon progress survives a page refresh.** Killed monsters, opened gates and puzzles are kept if you died or refreshed. Leaving the dungeon on purpose still resets it.
- **Conversation window:** closes by itself when you walk away from the person you are talking to.
- **Dungeons have a level requirement:** you cannot enter below the dungeon's minimum level. The Enter button shows the required level.

### Changed
- **Mana:** spells cost full mana at level 1, and the cost drops to half by level 20. Mana regeneration is much slower (about a third), in combat it is nearly zero, and sitting now gives 4× regeneration. Intellect from gear speeds up regeneration slightly.
- **Bear Form text** now shows the real numbers (maximum health bonus and % less damage taken) and follows talents.
- **Merchants:** separate Buy and Sell tabs. Equipment in the Sell tab shows the comparison with what you are wearing and whether you can use it.
- **Cooldowns:** a clock-style sweep over the icon, a bigger outlined number (yellow for the last 3 seconds), a dimmed icon while on cooldown, a short glow when the spell is ready again, and a light dim during the global cooldown instead of the dot.
- **Bonefields:** dead trees are drawn with a dark outline and a pale trunk, so it is clear what you cannot walk through.
- **Co-op description** no longer lists what is or isn't supported.
- **Minimap** shows "Click to open map". The old "Press M for the map" line in the quest tracker is removed.

## v0.5.0 – earlier changes (before release notes were started)

### Hunter and pets
- Bear and Wolf pets (Call Bear lvl 5, Call Wolf lvl 10, Dismiss Pet, Mend Pet), pet bar button with a key (F), passive by default and attacks on command or when you are in combat.
- Pets work in co-op: friends see them, they draw aggro, and their skills and damage show on every screen.
- Hunter shots need a minimum distance (70 px). Raptor Strike and Wing Clip for close range, plus a faster melee auto-attack.
- Pet balance nerfs: bear threat and Growl duration, wolf damage.

### Stats and items
- Primary stats: Stamina, Intellect, Strength, Agility. Attack crit and spell crit are separate.
- New item generator with a stat budget by quality, item level and slot. Old items are retired when a character loads.

### World
- The world is twice as big in each direction. Same zones and layout, longer travel, same number of mobs.
- New merchants in the five small camps (basic potions, buys junk).
- Zoomable, draggable world map (opened by clicking the minimap).

### Interface and fixes
- Second action bar (Shift+1–0).
- Players and NPCs drawn 20 % smaller.
- Spam-clicking Hit no longer attacks faster than the swing timer.
- Walking upward shows the correct animation.
- Friends' spells and arrows are visible in co-op.
