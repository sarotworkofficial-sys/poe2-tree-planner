# PoE2 Tree Planner

Static passive tree planner for Path of Exile 2, used by the "PoE2 Guru" Discord bot.
Open `index.html` with link parameters, for example:

- `?class=Warrior&style=Slam&level=30` — ready-made route for a class and playstyle
- `?class=Warrior&style=Bear,Fire&targets=Resolute+Technique&level=85` — mixed styles plus must-have nodes
- `?class=Sorceress&targets=Electric+Amplification|Power+Conduction&level=60` — pick nodes by name
- `?class=Sorceress&level=30&t=...` — any tree, node ids packed as base64

Point budgets: Lv 30 ≈ 36, Lv 60 ≈ 81, Lv 85 ≈ 108 (level points + quest books).

## Data and credits
- Passive tree data: [Path of Building Community (PoE2)](https://github.com/PathOfBuildingCommunity/PathOfBuilding-PoE2) `src/TreeData`
- Node icons and frames (`assets/`): Grinding Gear Games' official passive skill tree export.
  Path of Exile 2 and its art are © Grinding Gear Games. This is a fan-made tool, not affiliated with or endorsed by GGG.
