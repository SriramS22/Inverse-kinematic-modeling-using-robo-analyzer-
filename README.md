# EX NO.3-Inverse-kinematic-modeling-using-robo-analyzer-

 
## AIM: 
To analyze the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer and polt the graph of joint angle for a given  input end effector position .


### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
### Inverse Kinematics
 

Inverse kinematics is the use of kinematic equations to determine the motion of a robot to reach a desired position. For example, to perform automated bin picking, a robotic arm used in a manufacturing line needs precise motion from an initial position to a desired position between bins and manufacturing machines. The grasping end of a robot arm is designated as the end-effector. The robot configuration is a list of joint positions that are within the position limits of the robot model and do not violate any constraints the robot has.

 Most industrial robots are constructed of several independently controllable articulated joints. Each joint is connected to one or more of the other joints, sometimes in complex configurations. The end effector is attached at the end of the entire “kinematic chain”. When you move any one joint, this will affect the end effector’s pose in various ways.

This means that there is no simple, direct relationship between the end effector position and any one particular joint.

For example, if you want the robot’s end effector to move 1 mm linearly along the Z-axis, you may need to move all of the joints by a different amount.

Finally, inverse kinematics algorithms calculate the exact position of each of the robot’s joints required to reach your desired end effector pose.

### solving inverse kinematic model 
![image](https://user-images.githubusercontent.com/36288975/170622829-3fe97ef7-8ef1-44af-afae-b0954871aa0c.png)


![image](https://user-images.githubusercontent.com/36288975/170622902-f48fd9c7-f2ec-4fd5-904b-ea51be8298c3.png)

![image](https://user-images.githubusercontent.com/36288975/170622934-a3fd7f77-7eb2-4408-b66d-d6e3adbd1f99.png)

![image](https://user-images.githubusercontent.com/36288975/170622982-9c4d8b23-1563-4e17-9616-87bcc4f4501d.png)
![image](https://user-images.githubusercontent.com/36288975/170623020-f27efc12-bb58-4f62-840d-af544ac6689e.png)

### PROCEDURE:
##### 1.open the roboanalyzer software.
##### 2.select the robot and its degrees of freedom.
##### 3.change the values of X and Y wherever necessary.
##### 4.simulate the model for inverse kinematics.
##### 5.plot the graph between the joints.
##### 6.update the DH parameters of the link configuration and end effector configuration.







### SIMULATION 
## RPR ROBOT:
![1](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/68a94d7e-c2f3-4105-9b83-ca3e4e79ff7d)
![2](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/fff7a94d-48e3-4f99-a8e9-5d60c58fc0dc)


## 3R ROBOT:
![4](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/8aa3533c-9826-4883-8387-44967861a9b9)




 ### PLOT 
 ## RPR ROBOT:
 ![5](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/35459bf3-150d-41ee-8803-caff4df7f7cc)
![6](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/cd882c3d-3247-434f-a445-b4e96b581aec)

 
3R ROBOT:
 
 ![7](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/b45679d4-e3b2-40d4-9757-5b4948b32dfa)

 ![8](https://github.com/IamShakthi/Inverse-kinematic-modeling-using-robo-analyzer-/assets/117913445/850cb476-dc3d-4531-8882-d528107264cd)

 
 
 
 

### RESULTS :  
Thus,the inverse kinematics using DH parameters for a 3 dof planer and 3 dof articulated robot using roboanalyzer is analysed and the graph of joint angle for a given input end effector position is plotted.
