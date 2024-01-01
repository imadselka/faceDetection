# faceDetection
<h1>Introduction to OpenCV </h1>
<p>Now that we understand just how useful computer vision applications are, let’s examine a popular tool used to implement them. OpenCV is a computer vision library that supports programming languages like Python, C++, and Java.

The package was initially created by Intel in 1999 and was later made open-source and released to the public.

OpenCV allows developers and non-mathematicians to build computer vision applications easily without having to code them from scratch. The library has over 2,500 algorithms that allow users to perform tasks like face recognition and object detection.

Developers and data practitioners at well-established organizations like Google, Microsoft, IBM, and Intel make extensive use of the OpenCV library, which is currently free for commercial use.

In this article, we will use OpenCV to perform face detection in Python.

By the end of this tutorial, you will know how to:</p>
<ul>
  <li>
    Detect human faces in images with OpenCV in Python
  </li>
  <li>
    Perform real-time face detection in a live stream from a webcam
  </li>
  <li>
    Recognize and label celebrity faces in images
  </li>
</ul>
<h1>Intro to Haar Cascade Classifiers</h1>
<p>This method was first introduced in the paper Rapid Object Detection Using a Boosted Cascade of Simple Features, written by Paul Viola and Michael Jones.

The idea behind this technique involves using a cascade of classifiers to detect different features in an image. These classifiers are then combined into one strong classifier that can accurately distinguish between samples that contain a human face from those that don’t.

The Haar Cascade classifier that is built into OpenCV has already been trained on a large dataset of human faces, so no further training is required. We just need to load the classifier from the library and use it to perform face detection on an input image.</p>
<h1>Installing OpenCV for Python</h1>
<p>To install the OpenCV library, simply open your command prompt or terminal window and run the following command</p>
<h3>pip install opencv-python</h3>
<h2>For Python3</h2>
<h3>pip3 install opencv-python to install OpenCV</h3>
