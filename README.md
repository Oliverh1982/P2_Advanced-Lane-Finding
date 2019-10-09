This is version 1 of Advanced Lane Finding, the goals / steps of this project are the following:

* Compute the camera calibration matrix and distortion coefficients given a set of chessboard images.
* Apply a distortion correction to raw images.
* Use color transforms, gradients, etc., to create a thresholded binary image.
* Apply a perspective transform to rectify binary image ("birds-eye view").
* Detect lane pixels and fit to find the lane boundary.
* Determine the curvature of the lane and vehicle position with respect to center.
* Warp the detected lane boundaries back onto the original image.
* Output visual display of the lane boundaries and numerical estimation of lane curvature and vehicle position.

The first step is to calibrate the camera, the chessboard size is set to be 9x6; I will save the output file in
output_images/find_corners/ .

The second step is to apply a distortion correction, I will show an example in my code.

After correction, I will try to use gradients, color transforms, and use perspective transform to creative an binary image.

The next step is to detect lane pixels, determine the curvature of the lane and vehicle position with respect to center, I will also show the result in my source code.

The final setp is to wrap the detected lane boundaries back onto the original image. For images, I will save the result in output_images/find_lines/ ; for videos, I will save the image in output_videos/ folder.

V1.0(2019/03/12)
-first release 

V1.01(2019/03/14)
-fine tune the scale factor
