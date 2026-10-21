# Rimfrost – Roadmap

Bocka av med `[x]` när något är klart. Lägg till nya punkter längst ner i rätt sektion.

## Klart

### Co-op
- [x] Co-op i övervärlden (PeerJS, host + gäst)
- [x] Co-op i dungeons: gemensam instans, samma seed och nivåer för alla
- [x] Monster i dungeons delas mellan spelarna (hosten kör dem)
- [x] Spakar, runor och grindar synkas mellan spelarna
- [x] Delad kill, XP och loot inne i dungeons
- [x] Ny spelare går med i pågående dungeon i stället för att nollställa den
- [x] Co-op i dungeons testat med kompis och fungerar

### Utvecklingsverktyg
- [x] Dev-panel (`?dev` i adressen, knappen DEV eller tangenten under Esc)
- [x] Sätt level, guld, heal, god mode, teleport, gå in i dungeon, ge föremål
- [x] Balanstest med bot (1 monster, 3 monster, elit) och sparade resultat
- [x] Balanstest stöder Druid-former (caster, bear, wolf)

### Klassbalans
- [x] Mana: alla kostnader ×0,5
- [x] All spelarskada ×0,8
- [x] Skadejusterare per klass (Mage 1,15, Warrior 1,15, Druid 1,10, Paladin 0,70)
- [x] Warrior rustning 0,85 → 0,80
- [x] Druid björnform rustning 0,6 → 0,7
- [x] Klassroller bestämda (se nedan)

**Roller:** Paladin mycket bra solo · Warrior bra solo (tank) · Druid medel–bra · Hunter medel · Mage svår solo men mycket bra i grupp · Priest medel–svår solo men oumbärlig i grupp

## Pågår

- [ ] Hunter pets (Bear lvl 5 tank, Wolf lvl 10 dps): testa och balansera med dev-testet
- [ ] Pets i co-op (just nu avstängt)

## Planerat

- [ ] Ny utrustning och nya sprites (pausat tills vidare)
- [ ] Balansera om efter större ändringar (kör dev-testet igen)
- [ ] Testa klasserna i grupp (roller i co-op, inte bara solo)

## Idéer att utreda

- [ ] Fler dungeons eller svårighetsgrader
- [ ] Bättre krit-balans (stora attacker kan döda ett monster på en träff)
- [ ] Mage-specifik manahantering (egen identitet)

## Kända problem

- [ ] Gäst som ansluter medan hen är i en dungeon skickas ut ur den (avsiktligt, men kan göras smidigare)
- [ ] Dungeon stannar om hosten stänger spelet
