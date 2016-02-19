===============================================================================================
Linear SLAM: A Linear Solution to the Pose Feature and Pose Graph SLAM based on Submap Joining 
Version: 1.0
===============================================================================================


MATLAB and C/C++ sourse code for Linear SLAM: A Linear Solution to the Pose Feature and Pose Graph SLAM based on Submap Joining. 

-----------------------------------------------------------------------------------------------
Quick start
-----------------------------------------------------------------------------------------------

MATLAB Code

Run Main.m

C/C++ Code

In Linux

Install cmake and suitesparse
    - sudo apt-get install cmake
    - sudo apt-get install libsuitesparse-dev

Install Linear SLAM
    - cd LinearSLAM_C/linux
    - mkdir build
    - cd build
    - cmake ..
    - make
    - sudo make install
 
Run
    - LinearSLAM -path VicPark_200_local_maps -num 200 -meth DC -type 2DPF -p pose.txt -f feature.txt

If one wants to know all the commands, type 
    - LinearSLAM -help

In Windows

Open solution "LinearSLAM.sln" using Microsoft Visual Studio.
Complie and run.
We recommend to use Microsoft Visual Studio 2010 or higher version.

The code are accompanied by some simulation and experimental datasets, for both pose feature and pose graph, 2D and 3D.

2D Pose Feature Datasets
    VicPark 200 local maps
    VicPark 6898 local maps
    DLR 200 local maps
    DLR 3298 local maps
    8240 data 50 local maps
    35188 data 700 local maps

3D Pose Feature Datasets
    Simu 3D 870 Loop


2D Pose Graph Datasets
    Intel
    manhattanOlson3500
    city10000

3D Pose Graph Datasets
    parking garage
    sphere2500

-----------------------------------------------------------------------------------------------
Support
-----------------------------------------------------------------------------------------------

Linear SLAM

Version: 1.0

The code is not optimized in this version. Any questions, comments, suggestions, discussions and bug reports are welcomed. The authors will appreciate every suggestions and any efforts on optimizing the code. 

Please mail to Liang.Zhao-1@uts.edu.au


