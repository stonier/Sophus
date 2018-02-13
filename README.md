## Sophus

C++ implementation of Lie Groups using Eigen. 

### Packaging

This is a release fork of the upstream repository maintained for the ROS community in order to maintain stability across ROS distros. Please send any non-release related issues or pull requests upstream. 

The current release branch is *indigo*. Ros packages are available for indigo, jade & kinetic (built as a [3rdparty package](http://wiki.ros.org/bloom/Tutorials/ReleaseThirdParty)).

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

