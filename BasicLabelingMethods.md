### Lasso and Brush
Pretty self-explanatory if you have used Photoshop or any other kind of basic image editing software. With a brush, you just draw with the Wacom pen.
WIth the lasso, it is the same idea except you must use a single pen-stroke and then afterwards it fills inside the drawn lasso. 

### Fill 
**Selection -> Fill**
There are three fill options:
- Current Slice: fills in labels in the current slice
- All Slices: fills in labels in every slice *independently* 
- Volume: fills in labels based in every slice *dependently*

In other words, if you select the "All Slices" option, it is equivalent to choosing "Current Slice" for each individual slice. 
However, if you select the "Volume" potion, a voxel is not filled in unless it is enclosed by the label in the image stack (i.e. the voxels around
it in a given slice, and the voxels "below" and "on top" of it in the preceding and proceeding slices. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/FillExample.png" width = 600>

### Smooth
**Selection -> Smooth**
There are two smooth options:
- Current Slice: smooths labels in the current slice
- All Slices: smooths labels in every slice

The selected area is smoothed. I usually run this once before labeling anything, since it makes the surface renderings look better 
without adversely impacting any volume measurements later on.

### Grow
**Selection -> Grow**
Useful if you accidentally "under-labelled" a structure and wish to expand your selection. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/GrowExample.gif" width = 600>


### Shrink
**Selection -> Shrink**
Useful if you accidentally "over-labelled" a structure and wish to expand your selection.

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ShrinkExample.gif" width = 600>

### Interpolate
**Selection -> Interpolate**
If you make selections across multiple slices, it will interpolate the labels between unlabeled slices. 
