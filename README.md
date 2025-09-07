<h1 align="center">Invisibility Cloak</h1>

This is an implementaion of ‘Invisibility Cloak’ from "Harry Potter" using simple computer vision techniques in OpenCV. 

![gif showing execution](./screenrecording.gif)

This code is written in Python because it provides exhaustive and sufficient library to build this program. Here, this magical experience is created using an image processing technique called Color detection and segmentation. In order to run this code, you need an mp4 video named "video.mp4". A cloth of same color with no other color visible is used as the subject. Here a red cloth is used.

# Building and running

## Install Required Libraries

*Note: Create a virtual environment before installing dependencies with venv (optional)*

**OpenCV:** Itis a Python library that is designed to solve computer vision problems. OpenCV supports a wide variety of programming languages such as C++, Python, Java etc. Support for multiple platforms including Windows, Linux, and MacOS.

```python3
pip install opencv-python
```

**Numpy:** It is a general-purpose array-processing package. It provides a high-performance multidimensional array object, and tools for working with these arrays. It is the fundamental package for scientific computing with Python.

```python3
pip install numpy
```

**Time:** It is part of the standard library and provides functions for working with time-related tasks. It allows for operations such as getting the current time, formatting time, and pausing program execution.

>*It comes prebuilt in python and does not need installation* 


## Run the script

```python3
python script.py
```