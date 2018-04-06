The Unscented-Kalman-Filter-dev folder contains files for non-simulator version,
which I personally feel easier for debugging.

In order to run the codes, clone all files under the folder, delete folder build.
Then 
1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./UnscentedKF ../data/obj_pose-laser-radar-synthetic-input.txt output.txt