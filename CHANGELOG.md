# FRONTLINE Changelog

## Unreleased

### Added

- Added a cinematic view to Skirmish and Sandbox. **F11** hides the interface, cursor, and tactical markers while the battle and fog of war continue. **F** allows a lower camera angle while the view is active. **F11** or **Esc** restores the regular view.
- Added weather-responsive ground mist and a cinematic color and lighting preset. Compatibility renders terrain-following mist layers. Forward+ adds depth-based volumetric mist, screen-space reflections, and indirect lighting.

Verified in Godot 4 with Compatibility (OpenGL) and Forward+ (Vulkan). The checks covered control restoration, weather response, mist occlusion by solid objects, and ongoing battle simulation.
