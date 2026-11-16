# FRONTLINE Changelog

## Unreleased

The current development build includes the verified 0.46 combat milestone, plus the battlefield and presentation updates below.

### Added

- Army rally points and wide, shallow fords on River Front and Far Frontier give infantry and vehicle columns more ways to assemble and advance.
- A tactical ridge on River Front provides elevated ground near a bridge. Artillery impacts leave visible craters and scorched vegetation, and buildings show structural fractures before collapsing into debris.
- The unit panel shows equipment, current orders, and reasons a unit is waiting. Numbered control groups can be recalled from the keyboard or minimap.
- Directional armor changes the damage dealt to the front, sides, and rear of vehicles. Vehicle subsystem damage can slow movement or delay firing. Drivers and strongpoints can restore damaged systems through paid repairs.
- Repeated suppressive fire and artillery blasts can briefly slow infantry. A lethal direct tank hit on infantry now has a distinct impact effect.
- Cinematic View hides the interface, cursor, and tactical markers while the battle and fog of war continue. **F11** toggles the view, **F** lowers the camera angle, and **Esc** exits. Compatibility uses terrain-following mist layers. Forward+ adds depth-based volumetric mist, screen-space reflections, and indirect lighting.

### Changed

- Columns can switch crossings, replace their lead vehicle, and resume their orders after local combat. At a defended crossing, they can hold for artillery or infantry support, or reroute where the map allows.
- Reduced repeated calculations for fog of war and terrain sampling, and batched impact effects. Large-battle performance remains a development priority.

## 0.39.0 development baseline

- Updated the Dozor, Bastion, and Thunder with a consistent low-poly ground-vehicle style across both sides.
- Refined track and suspension motion over terrain, added articulated crew hatches, and updated the Thunder's deployable stabilizers to settle against the ground.
