# rpi-opencv-build

Decompress: `tar -xvf opencv.tar.bz2`

In case build issues:
http://www.pyimagesearch.com/2015/02/23/install-opencv-and-python-on-your-raspberry-pi-2-and-b/
http://www.pyimagesearch.com/2015/10/26/how-to-install-opencv-3-on-raspbian-jessie/

build without ffmpeg

`-D WITH_FFMPEG=OFF`

`cmake -D WITH_TBB=ON -D BUILD_NEW_PYTHON_SUPPORT=ON \
      -D WITH_V4L=ON -D INSTALL_C_EXAMPLES=ON \
      -D INSTALL_PYTHON_EXAMPLES=ON -D BUILD_EXAMPLES=ON \
      -D WITH_QT=ON -D WITH_OPENGL=ON -D WITH_VTK=ON \
      -D WITH_FFMPEG=OFF ..`
