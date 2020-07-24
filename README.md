# Computer Vision Projects - Classical and Modern Approaches
Contains Computer Vision projects implemented with OpenCV and Python.

Projects aimed at:
1. Classical Computer Vision Techniques
2. Advanced Computer Vision and Deep Learning
3. Object Tracking and Localization

## Project One: Facial Keypoints Recognition

In this project, I combined my knowledge of computer vision techniques and deep learning architectures to build a facial keypoint detection system that takes in any image with faces, and predicts the location of 68 distinguishing keypoints on each face! Facial keypoints include points around the eyes, nose, and mouth on a face and are used in many applications.

The project is broken down into four main parts:

[Notebook 1](FacialKeypointRecognition/1_LoadAndVisualizeData.ipynb): Loading and Visualizing the Facial Keypoint Data
[Notebook 2](FacialKeypointRecognition/2_Define_TheNetworkArchitecture.ipynb): Defining and Training a Convolutional Neural Network (CNN) to predict Facial Keypoints
[Notebook 3](FacialKeypointRecognition/3_FacialKeypointDetectionCompletePipeline.ipynb): Facial Keypoint Detection Using Haar Cascades and our trained CNN.
[Notebook 4](FacialKeypointRecognition/4_ApplicationsKeypoints.ipynb): Applications using Facial Keypoints

## Project Two: Virtual Pen and Eraser

I recently came across posts on linkedin, where people were drawing virtually on the screen, originally posted by Mr. Taha Anwar. So, I thought why not try it on my own! Though the original version works on color thresholding to extract the pen from the scene, I had a hard time(& changing light intensities in my background) finding a right range. Hence, I added an aruco marker(tag id: 0) to act as a pen. Feel free to use this version and build your version upon it. A couple of other id markers can work for various colors and even eraser.

![OK? OK](VirtualPen&Eraser/GIF_VirtualPen_2_Small.gif)

## Project Three: Custom Panaroma using OpenCV

In this mini-mini-project, I have build a custom panaroma script using Feature Matching through ORB algorithm. This is followed by Image Alignment after finding the Homogenous Transformation between the two images and applying perspective transformation to one of the image.

![Original Image 1](CreatePanaroma/Data/Photos/IMG_20200723_112355.jpg)
![Original Image 2](CreatePanaroma/Data/Photos/IMG_20200723_112359.jpg)
![Result](CreatePanaroma/Result.jpg)

# . . .




