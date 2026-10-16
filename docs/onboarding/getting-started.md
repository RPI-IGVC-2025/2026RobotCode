# Getting Started

## Initial Setup

For installation follow the `install.md` file to get everything set up.
Remember to keep docker open and running when you try to open the container or it will not work.

Also, the first time the container is made, and every subsequent remake, it will take some time to download the dependencies. Don't be scared by how long that takes as it will be a while depending on how good your machine is.

## Verifying the Environment

Once everything is installed and ready check to make sure these work:

- ROS2: run the commands in install.md
- Gazebo: do Ctrl-Shift-P and click `Tasks: Run Task` and click `IGVC: Run Simulation` and see if the application opens
- Nav2: do Ctrl-Shift-P and click `Tasks: Run Task` and click `IGVC: Open Nav2` and see if the application opens

If all of these launch correctly, your container is probably configured properly.

## Learning ROS2

After completing setup, I moved on to learning basic ROS2 concepts.

I used the [Official Ros2 Tutorials](https://docs.ros.org/en/foxy/Tutorials/Beginner-CLI-Tools/Introducing-Turtlesim/Introducing-Turtlesim.html). Ignore the set up though, because the container already has everything you need. 

Do everything under the `Beginner: CLI Tools` and nothing else, as by the end of it you should have a grasp of the basic node structure of ROS2.

## Almost Done

Now ou should have the basics set up and ready. To continue learning how the robot will function , go to learning resources and get a feel for the other tools and resources you will need.

