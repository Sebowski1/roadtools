# Common issues 

## Before you start
- Blender: 4.0+ 
- OS: Windows/macOS/Linux
- Add-on version: 1.0

## Drawing tools snap incorrectly
- **Cause:** Angle Snap enabled / wrong custom angle.  
- **Fix:** Disable Angle Snap or set desired angle.

## Intersections look broken
- **Cause:** Overly dense mesh causes the shape to become mangled up.
- **Fix:** Dissolve vertices that are too close to eachother with `Ctrl+X`.

## Intersections disaply "Incorrect shape"
- **Cause:** Intersections are too "sharp" or a point is too close to a nearby intersection
- **Fix:** inscrease the `Radius` for the right vertecies in the `Edit Road` subpanel or if the error happens on a road ending, move it further apart from the nearby intersection. 

## Can't add road object after deleting the previous one
- **Cause:** When trying to re-add the road object, the original data from the previous road object (assets, materials, nodegroups) are still in the file
- **Fix:** Try deleting the unused datablocks by purging the unused data `F3` >>> `Purge Unused Data`, or `File` >>> `Cleanup` >>> `Purge Unused Data`. You should do this cleanup anytime you delete a road object to prevent your blender file from having a lot of unused datablocks

## Traffic lights not animating after baking
- **Cause:** The Bake option set to *Still* by default. This casues the road shape to be     
- **Fix:** In Geometry Nodes Modifier, set Bake Node to *Animation*, then **Bake Road** again.

## How to get logs
- Open **Window > Toggle System Console** (Windows) or run Blender from terminal.
- Reproduce the issue and copy errors to your bug report.
