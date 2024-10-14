# Gazebo_hackathon

Go to the master branch to access all files.

## Steps

1. Download this branch completely.
2. Put the following commands in the terminal, in the path of this folder:

    ```bash
    catkin_make
    source devel/setup.bash
    ```

### To View the Model in RViz (this works completely):

    ```bash
    roslaunch manipulator display.launch
    ```

### To View the Model in Gazebo (issue: the links on the gripper keep flying away):

    ```bash
    roslaunch manipulator gazebo.launch
    ```

### To Run Path Planning:

    ```bash
    roslaunch movit_manipulator_sim full_manipulator.launch
    ```

1. Select the final pose as the pose you want.
2. Click **Plan & Execute**.

