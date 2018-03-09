# Autonomous Robot

To see the robot action, please download the repository and open the file home.html in Firefox  
*Chrome does NOT work  

### Forward Kinematics 
* W A S D - Move the Robot  
* J K - Toggle between Robot Joints  
* U I - Increment/Decrement Rotation Angle of Selected Joint  
* Q E - For Lateral Base Movement  
* O - Servo based on system seconds  

*the blue and dark green boxes represent the rendering geoms for the robot's forward and lateral directions

### Inverse Kinematics 
* P - Make Robot Endeffector(navy blue) move towards the Target Point(light green)  
* R F - Move the Target Position Up and Down  

### Path Finding  
* M - Start the process of Path Finding
* B N - move through the found robot path
* Motion Planning is implemented using RRT-Connect algorithm (described by Kuffner and LaValle)
* Yellow dots represent possible valid robot configuration
* Once the path is found it shown using red dots
