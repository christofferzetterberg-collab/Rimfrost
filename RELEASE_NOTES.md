<!-- For the maintainer: the character select screen shows the three newest sections of this file. Keep the heading format "## vX.Y.Z – date", "### Added/Changed/Fixed" headings and "- " bullets. Only write what a player needs to know. -->
# Rimfrost – Release notes

Newest version first.

## v0.11.0 – 2026-10-23
### Added
- **Display and controls settings** in the menu. Change the zoom (on phones and on PC), and on phones the size of the joystick and the buttons, which side the joystick is on, and which buttons are shown. Your choices are saved, and there is a reset button.
- **Click pets on the field** to select them, your own pet or a friend's, just like clicking a player. A selected pet gets a ring around it.
- **Click your own portrait** to select yourself again after selecting a friend. Your portrait is highlighted when your heals and buffs go to you.

### Changed
- **Phones are no longer too zoomed in.** The extra zoom from the last update now only applies on PC. You can still change it in the settings.

## v0.10.0 – 2026-10-23
### Added
- **All four dungeons are rebuilt from scratch.** The Iron Mine, the Drowned Temple, the Ember Forge and the Frost Vault each have their own layout, with branching rooms instead of one long corridor, and their own mix of puzzles and dangers.
  - **Keys and locked doors:** find a key in an old chest, often guarded by a miniboss, and use it on a locked door.
  - **Secret rooms:** cracked walls can be examined to open a hidden room with a treasure chest (gold and a rare or better item).
  - **New puzzles:** pressure plates and heavy blocks you push onto them (an altar resets the blocks if you get stuck), alongside the levers and the rune puzzle.
  - **A unique hazard in each dungeon:** collapsing floors in the Iron Mine, flooding pools in the Drowned Temple, erupting lava vents in the Ember Forge and freezing ice in the Frost Vault.
  - **Boss fights have phases:** at 70 %, 40 % and 15 % health the boss calls in reinforcements, and marked areas on the floor show where its attacks will land. Move out of the circle in time.
  - **Solo and group modes:** the dungeon adapts to your party. Alone it is a solo run. In co-op the monsters are tougher, the boss calls more reinforcements, and pressure plates have to be held by the whole group.
- **Chest rolls in a group.** When someone opens the treasure chest in a dungeon, everyone inside rolls 1–100 and the highest roll wins the gold and the item. The result is shown to everyone, in the log and in the chat. Alone there is no roll.
- **Party bars show more.** Your friends' mana, rage, energy or focus bar is now shown under their health in the party list.
- **Pets in the party.** Your own pet and your friends' pets now appear in the party list with health and energy or rage. Click a friend's pet to select it, and your heals go to it.

### Changed
- **The Mountain Troll is now a Goblin.** The monsters on Iron Ridge are goblins with their own look. The quests are now "Goblins of Iron Ridge" and "Goblin Fangs", and they drop Goblin Teeth. Quest progress you already had carries over.
- **The Cave Bear** in the Iron Mine and the **Vault Ice Bear** in the Frost Vault now look like real bears. The Cave Bear is large and dark brown, and the Vault Ice Bear is large and white.
- **Ice Bears are now properly white** and keep their shading, instead of looking like ghosts.
- **Chests can only be opened out of combat.**
- **Clicking on empty ground** now clears your current target.
- **The chat window only opens with the Enter key.** Clicking on it no longer starts typing by accident.
- Dungeon progress you had saved before this update is reset.

## v0.9.1 – 2026-10-23
### Fixed
- **Co-op:** players no longer drop out and rejoin over and over when their game window is in the background or minimized. A player is now only counted as disconnected after 20 seconds of silence.
- **Chat:** "joined" is only shown the first time a player joins, not every time the connection recovers.

## v0.9.0 – 2026-10-23
### Added
- **Co-op chat:** a small chat window on the left side while you play co-op. Press Enter to write, Enter again to send, Esc to cancel. The history lasts for the session, and the window fades when nobody is talking. Click it to write. The key can be changed under Keybindings.
- Chat also shows when someone joins or leaves the game.

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
