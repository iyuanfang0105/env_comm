[TOC]

# overview
this is a hand by hand document of installation of opencv
OS: Ubuntu 14.04
opencv: 3.3

# dependencies
```
sudo apt-get install build-essential # compiler
sudo apt-get install cmake git libgtk2.0-dev pkg-config libavcodec-dev libavformat-dev libswscale-dev # required
sudo apt-get install python-dev python-numpy libtbb2 libtbb-dev libjpeg-dev libpng-dev libtiff-dev libjasper-dev libdc1394-22-dev # required
```

# source code 
download the source code from github
http://opencv.org/opencv-3-3.html

# compile and build
```
cd ~/opencv
mkdir release
cd release
cmake -D CMAKE_BUILD_TYPE=RELEASE -D CMAKE_INSTALL_PREFIX=/usr/local ..
make
sudo make install

```


