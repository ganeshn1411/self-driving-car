SetUp and Run

Step 1 : Download Unity engine from : https://unity3d.com/

Step 2 : Download the appropriate game build of the self driving car package from : https://github.com/udacity/self-driving-car-sim

Step 3 : Set up the environment with the right set of packages:

    conda env create -f environments.yml

Step 4 : Drive the car in Train Mode

Step 5 : Train the model

    python model.py

    This will create model.h5

Step 5 : Drive the car in Autonomous mode

    python drive.py model.h5


Credits: https://github.com/udacity/CarND-Behavioral-Cloning-P3