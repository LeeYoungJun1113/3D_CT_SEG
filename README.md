# LUNG-SEG.
Lung Segmentation using U-net 

Overview
This notebook follows the work on lung segmentation. 
Our motivation is to automatically identify lung opacities in chest x-rays.

Medical Image Segmentation is the process of automatic detection of boundaries within images. In this exercise, we train a convolutional neural network with U-Net architecture, which training strategy relies on the strong use of data augmentation to improve the efficiency of available annotated samples.

The training is done with two chest x-rays datasets; One includes manually segmented lung masks, whereas the other was manually segmented by radiologists of the hospital. The lung segmentation masks were dilated to load lung boundary information within the training net and the images were resized to 512x512 pixels.
