# Getting Started With OpenCV
Instructions for Mac 10.10 Yosemite

*(Sorry, Windows folks! Anyone want to add instructions for Windows installation? Let me know and I'll give you access to this repository so you can add them.)*

## 1) Install the Python Anaconda bundle
From: http://continuum.io/downloads

Note: Be sure to select the Python 2.7 version--*not* the Python 3.4 version.

## 2) Install OpenCV
OpenCV can be frustrating to install, because it needs to be compiled (or "built").  This means you need to download the source code, and then run a few commands to "build" it on your computer.  Depending on how speedy your computer is, this can take an hour or two (I've even had it take up to 9 hours on a *very slow* Rapsberry Pi!).  So, make sure you have plenty of time set aside if you're building from source.  Fortunately, there's also an easier, pre-built option.  Here are instructions for both options:

### Easier (pre-built)
Go to your terminal, then run: `conda install -c https://conda.binstar.org/jjhelmus opencv`

This installs a pre-compiled version of OpenCV 2.4.10 from: [https://binstar.org/jjhelmus/opencv].  This is *not* the most recent version of OpenCV, but it spares you time it takes to compile it yourself!

### Harder (build yourself)
There's a great tutorial from Adrian Rosebrock on how to install the latest version of OpenCV and build it yourself from source: [https://www.pyimagesearch.com/2015/06/15/install-opencv-3-0-and-python-2-7-on-osx/]  

This tutorial uses a nifty little feature of Python called "virtual environments" that keeps OpenCV nicely contained and connected to the correct version of Python, and helps you avoid dependency issues that may arise when installing against your computer's default system Python.

## 3) Check out some OpenCV tutorials
* **Practical Python and OpenCV** by Adrian Rosebrock: [https://www.pyimagesearch.com/practical-python-opencv/]
* Find others?  Let me know, and I can add you to the repo so you can add them here!
