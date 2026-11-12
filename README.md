# Luki Item Inspector — 0.2.0 (source)

Minecraft Java 1.20.1 · Forge 47.4.2 · Java 17

## Current implementation
- G toggles inspection.
- Vanilla first-person hand passes are cancelled during inspection.
- The player's skin arms are rendered in the first-person view.
- The main-hand item (or offhand fallback) is rendered using its baked item model.
- Mouse movement is redirected into item yaw/pitch while inspection is active.
- Scroll wheel adjusts inspection distance.
- Opening a screen or losing the player exits inspection.
- Enter/exit uses a smoothed transition.

## Important testing status
This is a development source build, not a verified release JAR. It has not yet been compiled or tested in a running Forge client in this environment. Arm alignment and item placement must be checked in-game. The arms are rendered using the player's skin, but articulated two-handed grip animation / per-item hand poses are not implemented yet.

## Build
Use JDK 17 and Gradle with ForgeGradle access: `gradle build`
Output: `build/libs/LukiItemInspector-0.2.0.jar`
