# Duct-Ninja-Conduit-Service-Robot
Duct Ninja is a Service robot used to place the conduits inside the duct, specifically for circular duct shape.  The adorable robot has a spherical appearance and carries a little cape in the back. You can control the motion by using the user interface on the mobile phone.  

## Software Tool: 
- Python 
- Rhino 3D 
- Grasshopper 3D
- Prusa 3D Print Slicer
- Arduino
- 

## Hardware Tool:
- Arduino Uno x1
- Breadboard x1
- Powersupply 24V x1
- Ultrasonic Sensor x1
- DC Motor x2
- Servo Motor x3
- 3D Printing Part



![image](https://user-images.githubusercontent.com/65818525/131329303-3f400a96-c7cf-4d31-a11a-86d32c1469ed.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329384-8e037b66-717b-44b0-83bc-0de4d3a2c053.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329421-2dd79f84-6640-40d3-9f59-6fa949eec270.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329430-133e995a-6c0e-4f51-91ff-56534e81e05b.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329552-f5a68ddb-36f2-4602-957c-a6a74265dc57.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329606-d2ef423f-d81c-4b1e-9d37-7522fc818120.png)
---
- She is 16 cm tall; the width is 16 cm and consists of two main parts: the upper body and the bottom body with four support wheels. Inside the bottom body are the power-driven parts; the upper body part mainly includes the circuit and the vision. The upper body has one degree of freedom. Because of limited space, the servo motor should be laid flat. Therefore we choose bevel gear to change the rotation direction to rotate the robot head. The Lower body has four auxiliary wheels. And in the middle, there is a power-driven wheel. There is a module cap on the robot's backside, which can be changed with a customed module to carry different things. An Ultrasonic Sensor will also sense the surface height to adjust the central wheel to better adapt to the surface. The Lower body has 2 degrees of freedom. Gear A from servo motor A will rotate against gear B to rotate the main wheel. The servo motor B is used to drive the linear axis to change the height.
![image](https://user-images.githubusercontent.com/65818525/131329497-3d46d15c-6898-4909-a8a9-2822eca57df0.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329444-1f804f89-1e2a-4f3f-8827-58bab9892abe.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329644-e7c89c7a-df03-4828-bdcc-1bbaade162a3.png)
## Control System & User Interface
- Firefly in Grasshopper controls the systems. The OSB protocol is used to connect the mobile phone with the robot. A User interface on the mobile phone has been developed to control its motion. It is user-friendly, and it is easy to manipulate. There is an acceleration bar on the left, and you can use that with the forward/backward button. And the speed will show in different levels of the led amount; all the led light up means that it's on full speed running. And you can reset the Left-Right turn button on the right bottom by pressing the R button, and then it will reset the wheel back to the original orientation. For the Camera vision, you can change the bottom left slider to adjust the angle. The high led status is to show the distance level of the power wheel.
![image](https://user-images.githubusercontent.com/65818525/131329674-92e776f0-8db7-48d2-93b5-4dbf68f6c800.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329696-d711ee35-3a97-4cc9-a4c6-4e6186ca1fb0.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329738-1d0553f4-0ffb-4acf-98e5-f74b4ae81139.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329762-9c029545-7dde-4549-8516-a1436042a337.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329779-34145727-4ba6-4fad-8518-518ee37134ae.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329808-65890247-b7d4-45b1-90bd-3d36e2c03c34.png)
---
![image](https://user-images.githubusercontent.com/65818525/131329826-af024ad0-3f24-44a8-8980-428262005f04.png)

