Gaze Estimation through Machine Learning
=============================

_Machine Learning Course_

In order to learn machine learning we will follow relevant parts of an online course from California Institute of Technology by Yaser Abu-Mostafa named "Learning From Data". It is an introductory course, but it covers a wide variety of topics from regression-based learning to categorization-based learning to neural networks. 
The course assumes some knowledge of linear algebra and probability theory. 

_Project_

General: 

The project is about determining whether it is possible to use machine learning to identify at which point a person is looking (gaze estimation). 
It also requires the use of image analysis to extract information from the high-dimensional data of the eye images. 
The program will be programmed in Python, which has good support for image processing and machine learning algorithms through libraries. 

_Image Processing:_

The image processing part of the project will consist of extracting information from eye images, such that machine learning algorithms can be applied to the essential data. 
We will explore various processing algorithms both appearance based such as principal component analysis, and feature based where we try to find important aspects of the eye such as the iris, pupil and glint. 

_Machine Learning:_

The primary focus on the machine learning part is to use supervised learning to calculate a fitting function that can determine where the eye is looking. 
The machine learning techniques will be selected after taking the Caltech course, as we will have a better understanding of the domain. 


**Goals**

_Learn:_ 

Machine learning

Image processing, specifically principal component analysis

Python


_Determine:_

If it is possible to use the techniques we have learned to be able to automatically perform gaze estimation on static images, with a small margin of error 

_Produce:_

A program that, given a training set of images of eyes and the answer to where the eye is looking, will generate a function that takes an eye-image and returns the answer to where the eye is looking. 
As an image contains high-dimensional data, we will need to use image processing to reduce the amount of learning factors by extracting features from the image. 

To generate the training set and subsequent input-images, we will have a controlled environment where our test-subjects will be placed in a fixed position looking at a finite amount of points on a piece of paper, where the paper is located at a fixed position near the camera. We will then take several images of a test-subject looking at the points and mark the answers in the training-set.