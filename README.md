# Darkflow_YOLOV2_AMBEV
This Google Colab code shows the steps and code applied for the detection used on the beer labels


This Google colab code is a direct application of darkFlow (https://github.com/thtrieu/darkflow.git) applied to the AMBEV INOVA challenge.

# Steps to use the detection
1)Install dependencies: numpy, python-opencv, cython etc.
2)Install DarkFlow
3)Uninstall tensorflow and reinstall tensorflow 1.15
4)upload the images on the sample_img directory
5)Upload the tiny-yolo-voc-5c.cfg on the cfg folder and yolov2.weights on the bin folder.
6)upload all the 3500 bckp files insideckpt folder
7)Run the line 24: 

To use it, go to the line 24 and select a threshold to the detection. The test images should be put on the 
