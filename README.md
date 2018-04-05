[//]: # (Image References)

[image1]: ./images/obamas_with_keypoints.png "Facial Keypoint Detection"
# Facial Keypoint Detection and Real-time Filtering

## Project Overview

In this project, I have combined my knowledge of computer vision techniques and deep learning to build an end-to-end facial keypoint recognition system. Facial keypoints include points around the eyes, nose, and mouth on any face and are used in many applications, from facial tracking to emotion recognition. This project is able to take in any image containing faces and identify the location of each face and their facial keypoints, as shown below.

![Facial Keypoint Detection][image1]

The project will be broken up into a few main parts in one Python notebook:

__Part 1__ : Investigating OpenCV, pre-processing, and face detection

__Part 2__ : Training a Convolutional Neural Network (CNN) to detect facial keypoints

__Part 3__ : Putting parts 1 and 2 together to identify facial keypoints on any image


### Instructions and Requirements

Requirements can be seen in `requirements.txt` file.

The further instructions are provided in the `CV_project.ipynb`.
### Data

All of the data that has been used to train the neural network is in the this repo, in the subdirectory `data`. In this folder are a zipped training and test set of data.

1. Navigate to the data directory
```
cd data
```

2. Unzip the training and test data (in that same location). If you are in Windows, you can download this data and unzip it by double-clicking the zipped files. In Mac, you can use the terminal commands below.
```
unzip training.zip
unzip test.zip
```

You should be left with two `.csv` files of the same name. You may delete the zipped files.

