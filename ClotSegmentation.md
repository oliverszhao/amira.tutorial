# Clot Segmentation

There are five structures that need to be labeled:

- Blood Vessel Wall (Blue)
- Red Blood Cells (Red)
- Degranulated Platelets (Orange)
- Loosely Adherent Platelets (Yellow)
- Tightly Adherent Platelets (Green)

An example of these labels are shown below. Red blood cells are not always labeled. 
The blood vessel walls are fairly obvious, while the red blood cells are small, homogeneous, black, discoid shapes. 
Tightly adherent platelets typically make up the bulk or "skeleton" of the blood clot and appear as a dark grey. 
Meanwhile, degranulated platelets are a lighter shade of grey. Loosely adherent platelets, as their names suggest, appear loosely distributed. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ClotSegmentationExample.png", width = 600>

# Platelet Segmentation

There are three structures (as of writing) that need to be labeled:

- Platelet Membrane (Green)
- Condensed Alpha Granules (Blue)
- Decondensed Alpha Granules (Yellow)

The platelet membrane is fairly self-explanatory. Meanwhile, the condensed alpha granule appear as (usually) homogeneous, dark grey ellipsoids. Decondensed alpha granules are usually larger, but similarly shaped and light grey or white colored.
