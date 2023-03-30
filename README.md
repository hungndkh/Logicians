## UnCiv Mod Logicians

This is an UnCiv mod, which adds a civilization and corresponding units and buildings. When playing against other players, this mod may seem unfair to others! The units and buildings were inspired by real programs or projects (sishe Inspiration.md). It is still a work in progress.

## Hosting
The repository that contains the mod is developed and maintained on Codeberg. However, since UnCiv needs a copy of the mod on GitHub to show up in the list, there is a copy on GitHub.

## Note about the images
The images are all black and white, because UnCiv otherwise makes them black and white itself. Therefore some pictures have been changed enormously.

### Image removal
If an organization / person here owns a project and does not want me to change and use the logo, they are welcome to open an issue.

## JSON Order

### Units
- `name`
- `unitType`
- `replaces`
- `uniqueTo`
- Empty line
- `requiredTech`
- `obsoleteTech`
- `upgradesTo`
- Empty line
- `uniques`
- Empty Line
- `hurryCostModifier`
- `strength`
- `rangedStrength`
- `range`
- `interceptRange`
- `movement`
- Empty line
- `attackSound`
- `promotions`
- `cost`

## Buildings
- `name`
- `replaces`
- `uniqueTo`
- Empty line
- `maintenance`
- Resources provided:
    - `happiness`
    - `food`
    - `culture`
    - `gold`
    - `faith`
- `cityStrength`
- `cityHealth`
- Empty line
- `requiredTech`
- `requiredBuilding`
- Empty line
- `uniques`
- Empty line
- `isNationalWonder`
- `cost`
