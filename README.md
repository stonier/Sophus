## Sophus

C++ implementation of Lie Groups using Eigen. 

### Branches

* devel : ament compatible version of the development branch
* catkin-devel : catkin compatible version of the development branch
* release/0.9.1-kinetic : the kinetic released version 

### Packaging

This is a development fork of the upstream repository maintained for the ROS community in order to maintain stability across ROS distros. Please send any non-release related issues or pull requests upstream. 

This fork will have a release targeted at ros2 ardent and beyond.

### Installation - CMake

```
$ cd Sophus
$ mkdir build
$ cd build
$ cmake ..
$ make
```

### Installation - Ament

```
$ mkdir -p ~/sophus_ws/src
$ cd ~/sophus_ws/src
$ vcs import < https://github.com/stonier/sophus.git
$ cd ~/sophus_ws
$ ament build
```

