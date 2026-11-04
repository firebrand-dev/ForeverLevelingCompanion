# Changes

The players' changelog, shown on the website (tools/build_site.py). The developers' record is CHANGELOG.md.

## 0.8.1.1 — 2026-11-04

Two fixes on top of 0.8.1, for the WoW: Forever launch. No new features. Tested with the game client 1.60.1.70755 on
our own private test server (not on the official realms).

- **FLC's "Quests" window now takes the game's quest tracker's place**, under the minimap and its clock (at any
  resolution), while the game's tracker is hidden. If you moved it, it stays where you put it.
- A step that needs a higher level now says the level ("Requires level 10") instead of "Requires level 0".

## 0.8.1 — 2026-11-03

- **First public version.** Leveling guides with an arrow, quest tracking and Party Mode (help a player, level
  together).
- **Guides window** (`/flc guides`): choose the guide to follow. Leveling routes by zone, dungeon and raid guides, only
  your character's, with their levels and your progress. Automatic gives the choice back to FLC.
- **Quests by themselves**: FLC accepts and turns in the guide's quests (never in combat, never with Shift held). On a
  reward choice FLC never picks: it marks the one that helps you, or the one a vendor pays most for. `/flc auto` or
  Options to turn it off.
- **Minimap button**: left click shows or hides FLC; right click, a menu with Guides, Loot Atlas, Party Mode,
  Appearance, Options and Report a bug. Shift + drag moves it.
- Dungeon (23) and raid (12) guides: the way in, the quest objectives inside, each boss in the game's order, the way
  out. Boss card with its abilities; what is not confirmed yet carries "(?)".
- Class and dungeon quest advisors, Smart Loot Advisor and Loot Atlas with a wishlist.
- Adaptive look: adapts to ElvUI, Tukui, NDui, RealUI, SpartanUI and GW2 UI, or to one of its own skins. Welcome setup
  on the first start (`/flc setup`).
- `/flc review` and `/flc bug` make a text to copy and report; `/flc version` tells you when someone in your group has
  a newer version.
