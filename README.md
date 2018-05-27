# SDCND_Term2_UKF

## Unscented Kalman Filter Project
The project uses an unscented kalman filter to estimate the state of the moving object from the noisy RADAR and LIDAR measurements of the position and velocity of an object.
- Here the RMSE values are lower than the tolerance value mentioned in the project rubric.

This project involves the Term 2 Simulator which can be downloaded [here](https://github.com/udacity/self-driving-car-sim/releases). Follow the instructions present in the classroom section 'uWebSocketIO Starter Guide' for the environment setup.

Once the install for uWebSocketIO is complete, the main program can be built and run by doing the following from the project top directory.

1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./UnscentedKF

I have used the codes present in the the sdcnd and referred the open forum portals.

## Run the Project
1. Clone this repo.
2. Make a build directory: mkdir build && cd build
3. Compile: cmake .. && make
  On windows, you may need to run: cmake .. -G "Unix Makefiles" && make
4. Run it: ./UnscentedKF

## Result
The result for the input file 'obj_pose-laser-radar-synthetic-input.txt' is RMSE X: 0.0693 Y: 0.0835 VX:0.3336 VY:0.2380 The output plot is shown in Output_obj_pose-laser-radar-synthetic-input.JPG present in 'output\Output_obj_pose-laser-radar-synthetic-input.JPG'

I have not committed the complete Eigen folder. The codes are available in classroom example Git project repository.
