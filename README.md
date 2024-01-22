## Transport robot_Innok INDUROS 
-这个项目是一个使用ROS2（机器人操作系统）制作的小车项目，通过RVIZ系统创建一个两轮小车模型，可以进行平移以及旋转运动，具有手动控制、自动驾驶和提前避障（可选做）的功能。通过使用这些功能，来实现小车在复杂环境下的优化路径运动（指通过选择多点优化成圆角曲线或B-spline曲线，并非只能路径规划），提高工作效率。\n
-1.实现手动控制小车移动（使用键盘或虚拟手柄）
-2.实现自动控制小车
![image](https://github.com/Guo-baiyi/Transport_robot/assets/120784487/ff020e82-0ca7-4e5d-ba0f-9048fba51613) 
<img width="741" alt="image" src="https://github.com/Guo-baiyi/Transport_robot/assets/120784487/9390dbcf-5fad-4cf4-9b62-0eb20556d232">


## Consists of 5 components:  

- **Chassis** is a box._250mm*400mm*1150mm  
- **left_wheel**_Tire Diameter_300mm_Tire width_200mm  
- **right_wheel**_Tire Diameter_300mm_Tire width_200mm  
- **caster_wheel**_Represented by the hemisphere_Tire Diameter_300mm  
- **shell**_On top of the chassis.

![image](https://github.com/Guo-baiyi/Transport_robot/assets/120784487/48104e2b-fdca-4692-8ee5-0ac0a42e17a9)

- **base_link** set to be the center of the two drive wheels, and it also the center of the rotation of the robot. so the rest of robot reference to that.  
![image](https://github.com/Guo-baiyi/Transport_robot/assets/120784487/4103c66b-4712-43a0-a28a-90abd90c6734)

![image](https://github.com/Guo-baiyi/Transport_robot/assets/120784487/1921fc2e-5d6c-47fd-b078-06267bee65be)

![image](https://github.com/Guo-baiyi/guo_baiyi/assets/120784487/255bc9ed-0fd2-4fd2-988f-8641577df210)  

## Technical Parameters： 
![image](https://github.com/Guo-baiyi/Transport_robot/assets/120784487/5a250651-94f5-4513-88d2-539453641b03)
