This is an OpenCV 4.0 based implementation of a monocular visual odometry algorithm.

<!-- ## Algorithm
Uses Nister's Five Point Algorithm for Essential Matrix estimation, and FAST features, with a KLT tracker.
More details are available [here as a report](http://avisingh599.github.io/assets/ugp2-report.pdf), and
[here as a blog post](http://avisingh599.github.io/vision/monocular-vo/). 

Note that this project is not yet capable of doing reliable relative scale estimation, 
so the scale informaion is extracted from the KITTI dataset ground truth files. -->

## Demo Video

![Monocular_Visual_Odometry](https://user-images.githubusercontent.com/71000616/150598237-3836dad4-3188-412d-95e9-ab07aad0ab1f.gif)

<!-- [![Demo video](https://img.youtube.com/vi/Q7G07Ji3tLc/0.jpg)](https://youtu.be/Q7G07Ji3tLc) -->

## Requirements
OpenCV 4.0

## How to compile?
Provided with this repo is a CMakeLists.txt file, which you can use to directly compile the code as follows:
```bash
mkdir build
cd build
cmake ..
make
```

## How to run? 
After compilation, in the build directly, type the following:
```bash
./vo
```
## Before you run
In order to run this algorithm, you need to have either your own data, 
or else the sequences from [KITTI's Visual Odometry Dataset](http://www.cvlibs.net/datasets/kitti/eval_odometry.php).
In order to run this algorithm on your own data, you must modify the intrinsic calibration parameters in the code.

<!-- ## Performance -->
<!-- ![Results on the KITTI VO Benchmark](http://avisingh599.github.io/images/visodo/2K.png) -->

## Contact
For any queries, contact: aayushgarg152@gmail.com

<!-- ## License
MIT -->
