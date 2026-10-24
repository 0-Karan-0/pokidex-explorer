# PokéDex Explorer

A fast, mobile-first PokéDex Explorer that lets you find any of the **1025 Pokémon** in seconds and instantly see **which one is the most powerful**.

Single HTML file. No frameworks, no build step, no dependencies.

## Features

- **Instant search** by name, PokéDex Explorer number or type (`pikachu`, `25`, `fire`)
- **Power rating**: every Pokémon gets a tier badge (S / A / B / C / D) and a power bar, based on total base stats
- **Rank** out of 1025 and "best stat" for each Pokémon
- **Filters**: 18 types, power tiers, Legendary, Mythical, and Generations 1–9
- **Sort** by Dex number, Power, Attack, Defense, Sp.Atk, Sp.Def, Speed, HP or A–Z
- **Details sheet** with a stats radar chart, stat bars and **type matchups** (weak to / resists / immune)
- **Direct link** on every card to the official Pokémon.com PokéDex Explorer page
- **Favorites** saved in your browser
- **Grid / List view**, 🌗 **Light / Dark theme**, 🎲 **Random Pokémon**
- **Mobile-first**: 2-column cards, sticky search, bottom-sheet details, swipe to the next or previous Pokémon
- **Fast**: ~80 KB, cards load in batches as you scroll, lazy-loaded images

## How "power" works

Power = HP + Attack + Defense + Sp.Atk + Sp.Def + Speed (base stats total).

| Tier | Power |
|------|-------|
| S | 600+ |
| A | 500–599 |
| B | 400–499 |
| C | 300–399 |
| D | below 300 |

## Usage

Just open `index.html` in a browser. To host it for free, enable **GitHub Pages**:
`Settings → Pages → Deploy from a branch → main / (root)`.

Share a specific Pokémon with a hash link, e.g. `https://<user>.github.io/<repo>/#25` opens Pikachu.

## Credits

- Stats and type data: [PokeAPI](https://github.com/PokeAPI/pokeapi)
- Sprites and artwork: [PokeAPI/sprites](https://github.com/PokeAPI/sprites)
- Links point to the official [Pokémon.com PokéDex Explorer](https://www.pokemon.com/us/pokedex)

## Disclaimer

This is an unofficial fan project. It is not affiliated with, endorsed by, or sponsored by Nintendo, Game Freak, Creatures Inc. or The Pokémon Company. Pokémon and all related names and images are trademarks of their respective owners.
