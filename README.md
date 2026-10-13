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
- Route 1 → **Viridian City** → **Viridian Forest** → **Pewter City** → **Route 3** → **Mt. Moon** → **Cerulean City** → **Cerulean Cave**, then **Route 5** → **Vermilion City** → **Diglett's Cave** and the **S.S. Anne**
- **Gyms**: Brock (Boulder Badge) in Pewter, Misty (Cascade Badge) in Cerulean and Lt. Surge (Thunder Badge) in Vermilion. The road east of Pewter opens once you beat Brock.
- **Vermilion**: the Pokémon Fan Club chairman gives you an **S.S. Ticket**; board the **S.S. Anne**, battle sailors and Blue, and help the seasick captain to get **HM01 Cut**, which clears the small tree blocking Lt. Surge's gym. Once you leave, the ship sets sail.
- **Fishing**: the Fishing Guru in Vermilion gives you an **Old Rod**. Face water and press A to fish for Krabby, Tentacool and the odd Psyduck.
- **Team Rocket** in Mt. Moon, hunting a rare Pokémon called MEW
- A retired scientist in Cerulean tells how MEW was found and MEWTWO was created, and gives you a **Master Ball** once you have the Cascade Badge
- **MEWTWO** waits at the end of Cerulean Cave; afterwards, the scientist's hint leads you to **MEW** in Viridian Forest
- Blue challenges you four times: in the lab, at Viridian's north exit, in Cerulean, and aboard the S.S. Anne
- Trainers who spot you when you walk into their line of sight, plus items to find on the ground
- Poké Centers (with a PC to store extra Pokémon) and Marts in Viridian, Pewter, Cerulean and Vermilion
- Black out and you wake at the last Poké Center you used (or at home), having dropped half your money

**Battles**
- **53 Pokémon**, including Voltorb, Electrode, Magnemite, Diglett, Krabby, Meowth, Drowzee, Bellsprout, Venonat, Machop and Tentacool, plus Mew and Mewtwo, each with full-size 48×48 front and 32×32 back sprites;
- Game Boy-style battle screen with the trainer slide-in with party Poké Ball icons, and an 8×8 font
- Wild and trainer battles: trainers send out several Pokémon, pay prize money, block Poké Balls and won't let you run
- 12 types (including Rock, Ground and Fighting) with immunities, STAB, critical hits, stat changes, EXP and level-ups
- Draining moves, Recover, Swift (never misses), Supersonic, Sing, Teleport (wild Abra escapes!), Sonicboom (always 20 damage), Selfdestruct, and Pay Day (pick up coins after the battle)
- **Status conditions**: poison, burn, paralysis, sleep and confusion, from moves like Poison Sting, Ember, Thunder Wave, Sleep Powder and Confusion. Poison also hurts while walking.
- **PP**: every move has limited uses; with none left you Struggle. Poké Centers, Mom and Oak restore PP.
- Moves learned by levelling up (e.g. Pikachu learns Thunder Wave at 9) and on evolving
- **Evolution**: Pokémon evolve at set levels (e.g. Charmander → Charmeleon at 12 → Charizard at 24). Hold or press B to stop it; it tries again at the next level.
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
