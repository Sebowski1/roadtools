# Common issues 

## Before you start
- Blender: 4.0+ 
- OS: Windows/macOS/Linux
- Add-on version: 1.0

## Drawing tools snap incorrectly
**Cause:** Angle Snap enabled / wrong custom angle.  
**Fix:** Disable Angle Snap or set desired angle.

## Intersections look broken
**Cause:** Overly dense mesh causing the shape to be mangled up.
**Fix:** Dissolve nearby vertices (`Ctrl+X`).

## Intersections disaply "Incorrect shape"
**Cause:** Intersections are too "sharp"
**Fix:** inscrease the `Radius` for the right vertecies in the `Edit Road` subpanel.

## Traffic lights not animating
**Cause:** The Bake option set to *Still* by default. This casues the road shape to be     
**Fix:** In Geometry Nodes Modifier, set Bake Node to *Animation*, then **Bake Road** again.

## How to get logs
- Open **Window > Toggle System Console** (Windows) or run Blender from terminal.
- Reproduce the issue and copy errors to your bug report.
