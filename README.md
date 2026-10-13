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

**Story and world**
- An intro with Professor Oak, where you pick your name
- Pallet Town and Oak's lab: choose **Bulbasaur, Charmander, Squirtle or Pikachu**. Your rival **Blue** takes the starter that's strong against yours and battles you on the spot.
- Route 1 → **Viridian City** → **Viridian Forest** → **Pewter City** → **Route 3** → **Mt. Moon** → **Cerulean City** → **Cerulean Cave**
- **Gyms**: Brock (Boulder Badge) in Pewter and Misty (Cascade Badge) in Cerulean. The road east of Pewter opens once you beat Brock.
- **Team Rocket** in Mt. Moon, hunting a rare Pokémon called MEW
- A retired scientist in Cerulean tells how MEW was found and MEWTWO was created, and gives you a **Master Ball** once you have the Cascade Badge
- **MEWTWO** waits at the end of Cerulean Cave; afterwards, the scientist's hint leads you to **MEW** in Viridian Forest
- Blue challenges you three times: in the lab, at Viridian's north exit, and in Cerulean
- Trainers who spot you when you walk into their line of sight, plus items to find on the ground
- Poké Centers (with a PC to store extra Pokémon) and Marts in Viridian, Pewter and Cerulean
- Black out and you wake at the last Poké Center you used (or at home), having dropped half your money

**Battles**
- **42 Pokémon**, including Mew and Mewtwo, each with full-size 48×48 front and 32×32 back sprites;
- Game Boy-style battle screen with the trainer slide-in with party Poké Ball icons, and an 8×8 font
- Wild and trainer battles: trainers send out several Pokémon, pay prize money, block Poké Balls and won't let you run
- 12 types (including Rock, Ground and Fighting) with immunities, STAB, critical hits, stat changes, EXP and level-ups
- Draining moves, Recover, Swift (never misses), Supersonic, Sing, and Teleport (wild Abra escapes!)
- **Status conditions**: poison, burn, paralysis, sleep and confusion, from moves like Poison Sting, Ember, Thunder Wave, Sleep Powder and Confusion. Poison also hurts while walking.
- **PP**: every move has limited uses; with none left you Struggle. Poké Centers, Mom and Oak restore PP.
- Moves learned by levelling up (e.g. Pikachu learns Thunder Wave at 9) and on evolving
- **Evolution**: all 8 families evolve (e.g. Charmander → Charmeleon at 12 → Charizard at 24). Hold or press B to stop it; it tries again at the next level.
- Catching with Poké, Great, Ultra and Master Balls; sleeping or poisoned Pokémon are easier to catch
- Rare Candy raises a level (and can trigger evolution)

**Items, money and menus**
- Start with ¥3000; earn more from trainers and wild battles
- **Poké Mart**: buy and sell Poké Balls, Great Balls, Ultra Balls, Potions, Super Potions, Antidotes, Parlyz Heals, Awakenings and Burn Heals
- Use items from the ITEM menu in battle or from the START menu
- **Pokédex** (from Oak): tracks every Pokémon seen and caught, with an entry page for each
- START menu: Pokédex, Pokémon (summary with stats and PP, switch order), Item, trainer card (with badges), Save, Autosave
- **Autosave** to the browser's local storage: every minute while exploring, after battles, healing and story events, and when you close the tab or switch apps. Saves from version 2 load and are upgraded.
- Original chiptune music for the title, towns, routes, the forest, caves, Poké Centers, battles, legendary battles and evolution

Pokémon is © Nintendo / Game Freak / The Pokémon Company. This is a non-commercial fan project.
