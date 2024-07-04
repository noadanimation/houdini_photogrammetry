# Houdini Photogrammetry
HDAs for processing photogrammetry scans in Houdini

## Photogrammetry align pair
For scans taken in two halves, this SOP node helps align those halves. It provides an interface to manually match features between the scan halves by adding matching points to each.

How to use:
- Link the geo for each scan half into the two inputs, ideally with textures visible to make it easier to match features. The first input will be aligned to the second input.
- With Mode set to "Align" (the default) both halves will be visible
  - Control-click on either half to add a pair of points to match between halves
  - Click-drag to move each point, so that each of the paired points are on the matching parts of each half
  - You'll need at least 3 matched points
- Set Mode to "Output" once complete, or "Preview" to see both halves of the scan aligned.
