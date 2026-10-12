# Pokémon Simple Game

A tiny Pokémon Red–style fan game that runs in the browser. Everything lives in one self-contained file, `index.html`: there's no build step and no dependencies, and all the art is drawn in code with the 4-shade Game Boy palette.

## Play

Open `index.html` in any modern browser.

| Action | Keyboard | Touch |
| --- | --- | --- |
| Move | Arrow keys | D-pad |
| Talk / confirm (A) | `Z` or `Space` | A |
| Back (B) | `X` or `Esc` | B |
| Menu (START) | `Enter` | START |
| Sound on/off | `M` | SOUND |

## What's in it

- An intro with Professor Oak, where you pick your name
- Pallet Town and Oak's lab: choose **Bulbasaur, Charmander, Squirtle or Pikachu**
- Route 1 with trees, paths, fences and tall grass
- Random wild encounters (Pidgey, Rattata, Caterpie, Weedle, and a rare Pikachu)
- Turn-based battles with types, STAB, critical hits, stat-lowering moves, EXP and level-ups
- Poké Balls with shake animations; caught Pokémon join your team (up to 6)
- **Evolution**: all 8 families evolve (e.g. Charmander → Charmeleon at 12 → Charizard at 24, Caterpie → Metapod at 7 → Butterfree at 10). Hold or press B to stop an evolution; it tries again at the next level. Each evolution teaches a new move.
- A start menu with your party, a summary screen, the bag, SAVE, and an AUTOSAVE switch
- **Autosave** to the browser's local storage: every minute while exploring, after battles, healing and story events, and when you close the tab or switch apps
- Healing at home (Mom) or in the lab (Oak, who also tops up your Poké Balls)

Pokémon is © Nintendo / Game Freak / The Pokémon Company. This is a non-commercial fan project.
