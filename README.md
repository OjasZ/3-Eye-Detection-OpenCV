
# Eye-Detection-OpenCV




Eye Detection using OpenCV

This repository contains a Python script that uses OpenCV to detect eyes in an image or video stream. The script is based on the Haar Cascade classifier, which is a machine learning-based approach to object detection.
## Tech Stack

**Client:** Lib, OpenCV, Python

**Server:** Node, Express


## Authors

- [@themutualguy](https://www.github.com/themutualguy)


## About 

Eye Detection using OpenCV

This repository contains a Python script that uses OpenCV to detect eyes in an image or video stream. The script is based on the Haar Cascade classifier, which is a machine learning-based approach to object detection.
Dependencies

The script requires the following libraries:

    OpenCV (version 4.0 or higher)
    Numpy

Usage

The script can be used to detect eyes in an image by running the following command:

python detect_eyes.py --image path/to/image.jpg

It can also be used to detect eyes in a video stream by running the following command:

python detect_eyes.py --video

You can also adjust the scale factor and minNeighbors for more accurate detection by adding --scale and --neighbors arguments respectively.

python detect_eyes.py --image path/to/image.jpg --scale 1.3 --neighbors 5

Results

The script will display the original image or video frame with rectangles drawn around the detected eyes. The detection can be adjusted by changing the scale factor and minNeighbors in the detectMultiScale method of the classifier.
Limitations

The Haar Cascade classifier is not always the most accurate method for object detection, and it may not work well with all types of images or video frames. The detection may also be affected by lighting conditions, facial expressions and angle of the face.
Contribution

We welcome contributions to this project. If you would like to contribute, please fork the repository and make changes to the code. Once you have made changes, please submit a pull request for review.
References

    OpenCV documentation: https://docs.opencv.org/
    Haar Cascade classifier: https://en.wikipedia.org/wiki/Haar-like_features
