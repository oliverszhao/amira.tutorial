## Purpose
Denoising has two major purposes in the context of platelet segmentation: (1) to make the images more visually clear and (2) to improve thresholding. 

In the image below, the first column is the raw image. Meanwhile, the second, third, and fourth columns have denoised images that are made with a Gaussian filter with varying extents of smoothness.

We see that for visualization purposes, a standard deviation of 1 is probably the best. 

In the second row, we apply a threshold to each image. We see that we aren't able to threshold the raw image well due to the noisy background. However, if we denoise the image first, then the thresholding is much more successful (albeit not perfect).

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/Thresholding.gif" width = 1200>

To segment the platelet membrane, we typically denoise the image and then threshold it. We then fill in the holes of the selected area.

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ThresholdingStep1.gif" width = 450>

We then select the platelet of interest, invert the selection, and remove the inverted selection from our label.

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ThresholdingStep2.gif" width = 450>

Then, we use our Wacom pen to outline the platelet membrane at any parts that are incorrectly thresholded.

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ThresholdingStep3.gif" width = 450>

Then we remove that selection. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ThresholdingStep4.gif" width = 450>

Finally, we select our platelet, invert the selection again, and delete the inverted selection again, to isolate our platelet. 

<img src="https://github.com/oliverszhao/amira.tutorial/blob/main/images/ThresholdingStep5.gif" width = 450>
