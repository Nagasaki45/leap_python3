Building LeapMotion for python 3
================================

This repo builds a python3 compatible version of the LeapMotion binaries by automating the instructions from [here](https://github.com/kitchenbudapest/vr).

In your python / LeapMotion project run:

    git clone https://github.com/Nagasaki45/leap_python3.git
    cd leap_python3
    ./build_leap_python3.sh

In your python code replace `import Leap` with `from leap_python3 import Leap`.

- Prerequisites: swig and g++.
- SDK version: 2.3.1-31549
