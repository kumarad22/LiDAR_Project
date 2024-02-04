# Point Cloud Registration
LiDAR are objects which works similar to RADAR but instead of radio waves, light waves are used.
Now, LiDAR sensors could also be used to get the 3D image of an area. 
## About the Project
Generally, we get multiple datasets from a LiDAR sensor which are basically collection of many points in different coordinated systems.
Our aim to align them such that we get a final 3D image. This process is called **`Point Cloud Registration`**.
## Approach
There are many alogorithms and different approaches to this problem. What I have tried to implement here is the **`Itereative Closest Point(ICP)`** method.
More details about it could be found at [this site](https://towardsdatascience.com/point-cloud-registration-classic-approaches-d6191302b0b2).
## Tech Stacks
I have solely used the opensource [Open3D library](https://github.com/isl-org/Open3D) for this purpose.
## Requirements
It is better to run the file as Colab notebook only as it might not run well on your computer due to the heavy tasks involved.
## References 
While writing the code, I majorly followed an Youtube Channel : [Amnah's Lab](https://www.youtube.com/@AmnahsLab)
