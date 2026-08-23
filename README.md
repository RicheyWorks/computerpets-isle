# Isle

**Pet Survival Island** — Open-world craft-survival driven by what your pets can actually do.

Part of the [ComputerPets](https://github.com/RicheyWorks/computerpets) universe. Map: [computerpets-ecosystem](https://github.com/RicheyWorks/computerpets-ecosystem).

> Status: **design scaffold**. Gameplay contract is frozen. Engine choice is the one in the brief. Implementation comes next.

## Loop

You are not a naked human. Rui climbs, Paint scouts water, Reed clears bugs. Isle is a long session; overlay pets used here are 'camping' and hidden on the desktop.

## Genre & engine

- Genre: **Open-world survival**
- Engine: **Unreal Engine**
- Stack: Unreal Engine 5 · craft/survival · pet abilities as tools · optional dedicated server
- Default surface: `7777`

## How you play

1. Drop on a canon-biome island.
2. Assign pets as tools (dig, fish, watch).
3. Night = sleep care or mood drop.
4. Extract = bring craft unlocks home, not a new species.

## Talks to

- computerpets-hearth (camp)
- computerpets-acre
- computerpets-quarry
- computerpets-visitation
- computerpets-lore

## Failure doctrine

Pet leftover on island after quit → auto-recall 15m. Dedicated server crash → local snapshot. PvP off by default.

Canon rules that never yield:

- 210 living kinds. No illegal hybrids.
- Overlay pets can get tired, sick, or hide. Tokens are not burned by a minigame.
- Desktop walk stays the main quest. Closing Isle must leave Rui walking.

## Layout

```
computerpets-isle/
  README.md
  LICENSE
  docs/DESIGN.md
  src/                implementation lands here
```

## Run (Windows)

```powershell
UE5: open Isle.uproject. Server: IsleServer.exe -port=7777
```

Meet Rui first via the [flagship start-here](https://github.com/RicheyWorks/computerpets/blob/main/docs/START-HERE.md). This game is optional.

## License

MIT. See [LICENSE](LICENSE).

---

*Two hundred ten living kinds. Keep them so a line does not go quiet.*
