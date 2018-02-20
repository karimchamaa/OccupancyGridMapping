# OccupancyGridMapping

Implementation of Occupancy Grid Mapping in C/C++ using openCV library to visualize the results
 
## Install OpenCV:
```sh
$ sudo apt install libopencv-dev
```
## Compile:
```sh
$ g++ main.cpp GridMapping.cpp SensorFusion.cpp -o app `pkg-config --cflags --libs opencv`
 ````
## Run:
```sh
./app
```
