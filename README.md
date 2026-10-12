# Pokémon Simple Game

A tiny Pokémon Red–style fan game that runs in the browser, drawn to look like the 1996 Game Boy originals. Everything lives in one self-contained file, `index.html`: there's no build step and no dependencies, and all the art is drawn in code with the 4-shade Game Boy palette.

## Play

Open `index.html` in any modern browser.

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys | D-pad |
| Talk / confirm (A) | `Z` or `Space` | A |
| Back (B) | `X` or `Esc` | B |
| Menu (START) | `Enter` | START |
| Sound: all / effects only / off | `M` | SOUND |

## What's in it

- An intro with Professor Oak, where you pick your name
- Pallet Town and Oak's lab: choose **Bulbasaur, Charmander, Squirtle or Pikachu**
- Route 1 with trees, paths, fences and tall grass
- Random wild encounters (Pidgey, Rattata, Caterpie, Weedle, and a rare Pikachu)
- Game Boy-style battle screen: full-size 48×48 front sprites and 32×32 back sprites for all 22 Pokémon (drawn from shapes, then outlined and shaded in the Game Boy style), the trainer slide-in with party Poké Ball icons, and an 8×8 font
- Turn-based battles with types, STAB, critical hits, stat-lowering moves, EXP and level-ups
- Poké Balls with shake animations; caught Pokémon join your team (up to 6)
- **Evolution**: all 8 families evolve (e.g. Charmander → Charmeleon at 12 → Charizard at 24, Caterpie → Metapod at 7 → Butterfree at 10). Hold or press B to stop an evolution; it tries again at the next level. Each evolution teaches a new move.
- A start menu with your party, a summary screen, the bag, SAVE, and an AUTOSAVE switch
- **Autosave** to the browser's local storage: every minute while exploring, after battles, healing and story events, and when you close the tab or switch apps
- Original chiptune music for the title, Pallet Town, Route 1, battles and evolution, plus a victory fanfare
- Healing at home (Mom) or in the lab (Oak, who also tops up your Poké Balls)

Pokémon is © Nintendo / Game Freak / The Pokémon Company. This is a non-commercial fan project.
