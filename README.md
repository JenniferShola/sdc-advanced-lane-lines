## Advanced Lane Finding
[![Udacity - Self-Driving Car NanoDegree](https://s3.amazonaws.com/udacity-sdc/github/shield-carnd.svg)](http://www.udacity.com/drive)


Hello! This is the writeup for my Advanced Lane Finding project. In this project, I wrote a software pipeline to identify the lane boundaries in a video, but the main output I created is a detailed writeup of the project.  **Check out the [writeup](https://github.com/udacity/CarND-Advanced-Lane-Lines/blob/master/P4.md) for this project and use it as a starting point for understanding the process I used for detecting lane lines.**

The Project
---

The goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

Important files:
---
All files marked as `P4` so `P4.ipynb` and `P4.html` are project solution files and can be open through the normal means.

To read through the solution (without downloading the project and running python), please visit `P4.md`.

`white.mp4` is the solution video that shows the software pipeline superimposed onto the practice video.

The images used for camera calibration are stored in the folder called `camera_cal`.  

The images in `test_images` were used for testing the pipeline on single frames. 

Examples of the output from each stage of my pipeline is located in the folder called `ouput_images`. 

The video called `project_video.mp4` is the original video my pipeline works well on.  

`example_writeup.pdf` shows an example provided by the instructor of a successful assignment.

