# FaceRecognition
A facial recognition system is a technology capable of identifying or verifying a person from a digital image or a video frame from a video source.

Our smart phones are able to use human face as a password to unlock the device, just like fingerprint, face are also unique and we can easily differentiate one from the other.

So the conclusion is that these technology used in many different ways just like form simply unlocking your phone to sending money and accessing personal data due to these technology the security increased.

Modules:
•	Ready the data set that means firstly we collect the sample image.
•	Then we create a model and trained it
•	And in last we perform prediction on our data

So, for these we are using the viola jones algorithm, these algorithm is an object recognition framework that allow the detection of image feature in real time.

Working :
So first we collect the lot of positive (images of face) and negative images and after collecting the images, training the classifier, for train the classifier we need to extract feature from images, for these we use Haar Feature based cascade classifires. So with the help of these file we extract the face, so we train trained something using face or non face and once the training is done the data that we have got we will be able to detect face from any images.

Library used in these project:

1. OpenCV  Library: OpenCV stands for open source computer vision and a computer vision is a way of teaching intelligence to machin and making them to see things just like human.
So, in simplest form Computer Vision is What allows computer to see and process visual data just like human.
Basically it mainly deals with real time things such as videos, images.

2. Numpy Library: Numpy is a hightly optimized library for numerical operations. In System Digital image are stored in the form of matrix, so when computer see a picture it see in the form of pixel matrix.
So, the digital images are 2D array of pixels, and Numpy library is a general perpose array processing package library. So it provides a high performance multi dimension array object and tools for working with these arrays ,which make the processing with image easier. So the openCV array are converted into numpy array.
