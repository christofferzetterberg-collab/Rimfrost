# Rimfrost

A 2D role-playing game in the browser, inspired by World of Warcraft.

## Play

Open `index.html` in a browser (double-click the file), or play online via GitHub Pages.

## Install as an app on your phone

The game is an installable web app (PWA) when it runs on GitHub Pages.

1. Turn on GitHub Pages: the repository on github.com → Settings → Pages → Branch: `main`, folder `/ (root)` → Save.
2. Open the address (e.g. `https://<username>.github.io/Rimfrost/`) on your phone.
3. iPhone: Safari → Share button → "Add to Home Screen". Android: Chrome → menu → "Install app".

Updates: push to GitHub as usual. The app fetches the new version by itself and shows "A new version of Rimfrost is available – tap to update". The file `sw.js` also lets the game work without an internet connection.

## Controls (keyboard, all keys can be changed under Esc → Keybindings)

- **W A S D** or the arrow keys: move
- **1–9, 0**: action bar
- **Left-click / Tab**: select an enemy
- **Right-click / T**: start attacking
- **E**: talk to people, mine ore, gather herbs, use dungeon objects
- **Q / R**: health potion / mana potion
- **X**: sit down and rest
- **Esc**: close windows, clear target, open the menu
- **C** character, **B** bag, **P** spellbook, **N** talents, **L** quest log, **M** map, **K** crafting, **H** information

On touch screens the game shows a joystick and on-screen buttons instead.

The game saves automatically in the browser.

## Art and licenses

- **Animated characters and weapons** (`assets/characters`, `assets/charactersV2`): Liberated Pixel Cup (LPC), used under **OGA-BY 3.0**. Authors: see the download page on OpenGameArt.org.
- **Weapon and item icons** (`assets/weapons`): **CC-BY 3.0**, author: [Ravenmore](https://opengameart.org/users/ravenmore).
- **Animals** (`assets/creatures`): **CC0**.
- **Orc warrior (enemy)** (`assets/monsters/orcwarrior.png`): **CC-BY 3.0**, author: Calciumtrice (OpenGameArt.org).
- **Orc and elf player bodies** (`assets/charactersV2/Orc/orc.png`, `assets/charactersV2/Elf/alv.png`): made with the Universal LPC Spritesheet Character Generator, licenses **OGA-BY 3.0 / CC-BY-SA 3.0 / GPL 3.0 / GPL 2.0**. Authors: bluecarrot16, JaidynReiman, Benjamin K. Smith (BenCreating), Evert, Eliza Wyatt (ElizaWy), TheraHedwig, MuffinElZangano, Durrani, Johannes Sjölund (wulax), Stephen Challener (Redshrike), Thane Brimhall (pennomi), laetissima, Matthew Krohn (makrohn), Manuel Riecke (MrBeast), Zi Ye, Nila122. Full list: `creditsAlv.txt` and `creditsOrc.txt`.
- **Elf sprites** (`assets/charactersV2/Elf`): **CC-BY 3.0**, author: [Vander96](https://opengameart.org/users/vander96).
- **Bosses** (`assets/bosses`): author: [Balmer](https://opengameart.org/users/balmer) (OpenGameArt.org).
- **Goblin, gargoyle and dragon** (`assets/monsters`, made from `assets/charactersV2/char`): **GPL 2.0**, author: [Mobile Game Graphics](https://opengameart.org/users/mobile-game-graphics).
- **Special effects** (`assets/fx`, made from `assets/specialeffects`): **CC0**.
- **Ground textures** (`assets/environment/ground.png`, made from Screaming Brain Studios hex textures): **CC0**.
- **Potions** (`assets/potions`): **CC0** (free to use).
- **Sound effects** (`assets/sfx`, made from "RPG Sound Pack", a spell sound pack and "Level up, Power up, Coin"): **CC0**.
- **PeerJS** (`assets/lib/peerjs.min.js`, used for co-op): **MIT License**, Copyright (c) 2015 Michelle Bu and Eric Zhang.
