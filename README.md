# Computer-Vision

Computer vision is a field of artificial intelligence (AI) that enables computers and systems to derive meaningful information from digital images, videos and other visual inputs — and take actions or make recommendations based on that information. If AI enables computers to think, computer vision enables them to see, observe and understand.

Computer vision works much the same as human vision, except humans have a head start. Human sight has the advantage of lifetimes of context to train how to tell objects apart, how far away they are, whether they are moving and whether there is something wrong in an image.

(From IBM Cloud Education: https://www.ibm.com/topics/computer-vision).




## Image Recognition
Image recognition refers to the task of inputting an image into a neural network and having it output some kind of label for that image. The label that the network outputs will correspond to a pre-defined class. There can be multiple classes that the image can be labeled as, or just one. If there is a single class, the term "recognition" is often applied, whereas a multi-class recognition task is often called "classification".

A subset of image classification is object detection, where specific instances of objects are identified as belonging to a certain class like animals, cars, or people.

(From Stack Abuse: https://stackabuse.com/image-recognition-in-python-with-tensorflow-and-keras/).

### Result.
1. It is recommended to save the "ipynb" file in Google Drive and then run in Colab.
2. Running on "http://8dea-35-236-139-140.ngrok.io"
3. Image used: File: Images > bmwi4_50.jpg

![image](https://user-images.githubusercontent.com/86708470/169081505-fe6b4237-add0-4deb-9747-c601a1645bfe.png)





## Image Processing
Image processing is a way to convert an image to a digital aspect and perform certain functions on it, in order to get an enhanced image or extract other useful information from it. It is a type of signal time when the input is an image, such as a video frame or image and output can be an image or features associated with that image. Usually, the Image Processing system includes treating images as two equal symbols while using the set methods used.

It is one of the fastest growing technologies today, with its use in various business sectors. Graphic Design forms the core of the research space within the engineering and computer science industry as well. 

Image processing basically involves the following three steps.
Importing an image with an optical scanner or digital photography.
Analysis and image management including data compression and image enhancement and visual detection patterns such as satellite imagery.
It produces the final stage where the result can be changed to an image or report based on image analysis.
Image processing is a way by which an individual can enhance the quality of an image or gather alerting insights from an image and feed it to an algorithm to predict the later things.

(From Great Learning Team: https://www.mygreatlearning.com/blog/introduction-to-image-processing-what-is-image-processing/).

### Result.
Image used: File: Images > bmwi4_50.jpg

![image](https://user-images.githubusercontent.com/86708470/169160123-3c7ade80-9386-4e71-bdcf-82b3933e0e16.png)






  ## Image Clasification
Image classification refers to a process in computer vision that can classify an image according to its visual content. For example, an image classification algorithm can be designed to tell if an image contains a cat or a dog.

Getting an intuition of how a neural network recognizes images will help you when you are implementing a neural network model, so let's briefly explore the image recognition process in the next few sections.

This section is meant to serve as a crash course/primer on Convolutional Neural Networks, as well as a refresher for those familiar with them.

### Result.
![image](https://user-images.githubusercontent.com/86708470/169176558-2fe0b411-387a-4b80-8b81-ecf661dad6c1.png)





## Feature Extraction
Feature extraction refers to the process of transforming raw data into numerical features that can be processed while preserving the information in the original data set. We have SIFT, SURF, ORB and other techniques to get keypoints.

Scale Invariant Feature Transform (SIFT) is a feature detector developed by Lowe in 2004. Although SIFT has proven to be very efficient in object recognition applications, it requires a large computational complexity which is a major drawback especially for real-time applications. There are several variants and extension of SIFT which have improved its computational complexity.

Speed up Robust Feature (SURF) technique, which is an approximation of SIFT, performs faster than SIFT without reducing the quality of the detected points. Both SIFT and SURF are thus based on a descriptor and a detector. Binary Robust Independent Elementary Features (BRIEF) is another alternative for SIFT which requires less complexity than SIFT with almost similar matching performance.

Oriented FAST and Rotated BRIEF (ORB) as another efficient alternative for SIFT and SURF.

### Result.
![image](https://user-images.githubusercontent.com/86708470/169873340-340b86f1-626c-495e-8043-76957fabe5bc.png)





 ## Feature Matching
The basic idea of feature matching is to calculate the sum square difference between two different feature descriptors.

In brute-force matcher we have to match descriptor of all features in an image to descriptors of all features in another image. It is extremely expensive as we know any brute-force algorithm will guarantee getting a solution, but doesn’t guarantee getting optimal solution.

FLANN (Fast Library for Approximate Nearest Neighbors) is an image matching algorithm for fast approximate nearest neighbor searches in high dimensional spaces. These methods project the high-dimensional features to a lower-dimensional space and then generate the compact binary codes.

### Result.
![image](https://user-images.githubusercontent.com/86708470/169873426-f7779639-af47-471d-bf45-cccb762676af.png)






 ## Homography
Note that the homography matrix is a mapping between two planes. We have considered it here as a mapping from the image plane to a physical plane, but it could map between two image planes. The inverse of a homography will also provide the reverse mapping between the two planes.

The RANdom SAmple Consensus (RANSAC) algorithm proposed by Fischler and Bolles is a general parameter estimation approach designed to cope with a large proportion of outliers in the input data. Unlike many of the common robust estimation techniques such as M-estimators and least-median squares that have been adopted by the computer vision community from the statistics literature.

### Result.
![image](https://user-images.githubusercontent.com/86708470/169875989-36d8764d-e1e0-48f8-8e47-ef9a898434a5.png)





 ## Skeletons
In shape analysis, skeleton (or topological skeleton) of a shape is a thin version of that shape that is equidistant to its boundaries. The skeleton usually emphasizes geometrical and topological properties of the shape, such as its connectivity, topology, length, direction, and width. Together with the distance of its points to the shape boundary, the skeleton can also serve as a representation of the shape (they contain all the information necessary to reconstruct the shape).

Skeletons have several different mathematical definitions in the technical literature, and there are many different algorithms for computing them. Various different variants of skeleton can also be found, including straight skeletons, morphological skeletons, etc.

### Result.
![image](https://user-images.githubusercontent.com/86708470/169878415-82176212-8617-4513-b4d3-633debab2b90.png)
