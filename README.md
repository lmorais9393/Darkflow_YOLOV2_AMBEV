# Darkflow_YOLOV2_AMBEV
This Google Colab code shows the steps and code applied for the detection used on the beer labels


This Google colab code is a direct application of darkFlow (https://github.com/thtrieu/darkflow.git) applied to the AMBEV INOVA challenge.

# Steps to use the detection
1)Install dependencies: numpy, python-opencv, cython etc.

2)Install DarkFlow

3)Uninstall tensorflow and reinstall tensorflow 1.15

4)upload the images on the sample_img directory

5)Upload the tiny-yolo-voc-5c.cfg on the cfg folder and yolov2.weights on the bin folder.

6)upload all the 3500 bckp files inside ckpt folder

7)Run the line 24: %cd /content/darkflow
                   !./flow --model cfg/tiny-yolo-voc-5c.cfg  --imgdir sample_img/ --load 3500 --threshold 0.25 --labels labels.txt --gpu 1.0
                   
                   You can eventually change the threshold to another number
