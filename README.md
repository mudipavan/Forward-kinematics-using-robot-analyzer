# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
open the robot analyzer software. select the robot and its degrees of freedom. change the values with the link length whenever necessary. simulate the model for forward kinematics. pick the graph between the link and the joints. update the DH parameters of the link configuration and endeffector configuration.




### SIMULATION 
 6DOF
 
KUKA KRS ARC ROBOT
 
![image](https://user-images.githubusercontent.com/94828517/204585469-ded09b5e-620a-4930-98d9-f2a7e0024514.png)
![image](https://user-images.githubusercontent.com/94828517/204585579-761cb782-b6af-4808-aae3-75193ef6b6d4.png)

4DOF

![image](https://user-images.githubusercontent.com/94828517/204585777-a391e1c1-0015-42e6-ab7d-0d39c1b6a688.png)
![image](https://user-images.githubusercontent.com/94828517/204585843-dfe4dfc2-f53a-4288-8b49-eab004b7d859.png)


PLOT :

6DOF GRAPH

![image](https://user-images.githubusercontent.com/94828517/204586082-59a4f6e9-2f8f-4618-bf5c-e12dc5752504.png)

4DOF GRAPH

![image](https://user-images.githubusercontent.com/94828517/204586204-5bffb193-2a5f-4b11-adb5-8010703ada0c.png)


 
 
 
  
 
 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :
Thus the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.
