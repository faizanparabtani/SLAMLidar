# SLAMLidar
Simulating 2D LIDAR sensor used in SLAM

Simultaneous localization and mapping (SLAM) is the computational problem of constructing or updating a map of an unknown environment while simultaneously keeping track of an agent's location within it. While this initially appears to be a chicken-and-egg problem there are several algorithms known for solving it, at least approximately, in tractable time for certain environments.

### Use in Autonomous Vehicles
Autonomous Vehicles use LIDAR sensors to generate a 3D point cloud of the entities present around the ego vehicle. This helps in mapping and localization of the vehicle. Filtering is done to the point cloud obtained inorder to increase the efficiency and reduce computation time. Example: Objects belonging to a class like tree mainly the overhanging canopy which is indifferent to the task of Autonomy are filtered out.


### This video demonstrates the working
pygame is used to simulate this along with a basic floormap with blackborders indicating an obstruction. 
The script detects black borders in 2D space and then draws the same on top of the original map.

https://user-images.githubusercontent.com/52961945/126902831-5e201aac-9641-4597-a6d2-a0e1f25b81c6.mp4

#### Packages required
numpy
pygame
