# Image-And-Point-Cloud-Segmentation
Automatic image processing is a key component to many AI systems, including facial recognition and video compression, instance segmentation of images and point cloud data. One basic method for processing is segmentation, by which we divide an image into a fixed number of components in order to simplify its representation. For example, we can train a mixture of Gaussians to represent an image, and segment it according to the simplified representation as shown in the images below.
![CME Ver Image Prague](/inputCMEMap.JPG)

Or we could perform a clustering of point cloud in order to separate different objects, backgrounds etc, as shown in the image below
![CME Ver Image Prague](/inputCMEMap.JPG)

In this project, we perform image compression and point cloud segmentation. To this end, we implement Gaussian mixture models and iteratively improve their performance. First perform segmentation on the "Bird" (bird_color_24.png) and at the end run your algorithm on 3D point cloud data.

