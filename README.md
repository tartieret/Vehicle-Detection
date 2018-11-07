# Vehicle-Detection

In this project, I implemented a pipeline to detect vehicles in images. The following steps were performed:

1. Extract features using Histogram of Oriented Gradients (HOG) on a labeled training set of images 

2. Train a Linear Support Vector Machine classifier

3. Implement a sliding-window technique and use the trained classifier to search for vehicles in images.

4. Run the pipeline on a video stream and create a heat map of recurring detections frame by frame to reject outliers and follow detected vehicles.

5. Estimate a bounding box for vehicles detected.

The end result is shown below, with the full code available in the jupyter notebook. 

![alt text](./output_images/example.png)

## Training data

Here are links to the labeled data for [vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/vehicles.zip) and [non-vehicle](https://s3.amazonaws.com/udacity-sdc/Vehicle_Tracking/non-vehicles.zip) examples to train the classifier.  These example images come from a combination of the [GTI vehicle image database](http://www.gti.ssr.upm.es/data/Vehicle_database.html), the [KITTI vision benchmark suite](http://www.cvlibs.net/datasets/kitti/), and examples extracted from the project video itself.  
