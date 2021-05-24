Volume rendering is a useful tool that allows us to visualize an image stack with little to no segmentation labels. 

Every voxel in an image stack has a specific value (e.g. 0 to 255 or 0 to 65535). 

With volume rendering, we essentially modify two variables for each voxel value: (1) alpha transparency and (2) color. 

By modifying these two attributes based on voxel value, we can create useful visualizations that provide qualitative insights. 

For example, consider the image stack shown below:

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/Volume1.png" width = 900>

To create a volume render, we must open a **Volume Render** node. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/Volume2.png" width = 900>

To edit the color map, we click on the **Volume Render** node and click on *edit colormap*. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/Volume3.png" width = 900>

To edit the base transparency, click on the **Volume Render** node and change the *opacity* setting. However, notice that on the color map, we can also edit the transparencies for each voxel value.

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/Volume4.png" width = 900>

By tweaking the color map and transparencies, we can bring out details in the image stack. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/Volume5.png" width = 900>
