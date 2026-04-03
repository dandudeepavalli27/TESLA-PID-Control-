# TESLA-PID-Control
Aim
To compute the proportional control output using PID control.
General Objective
To understand PID control and how proportional gain influences system response in feedback control systems.
Specific Objective
To compute control output using:
u
=
K
p
⋅
e
u=K 
p
​	
 ⋅e
Given:
Error 
e
=
12
e=12
Proportional Gain 
K
p
=
0.12
K 
p
​	
 =0.12
Dataset
PID Line Following Dataset
Source: PythonRobotics
Procedure
Input error value
Input proportional gain
Apply PID formula
Compute control output
Display result
Algorithm
Start
Input 
e
e and 
K
p
K 
p
​	
 
Compute 
u
=
K
p
×
e
u=K 
p
​	
 ×e
Display result
Stop
Code Logic
u = Kp * error
Python Code
# SESSION 40 – PID Control (Proportional)

# Step 1: Input values
error = 12
Kp = 0.12

# Step 2: Compute control output
u = Kp * error

# Step 3: Display result
print("Control Output =", u)

print("\nProgram Executed Successfully")
Output
Control Output = 1.44

Program Executed Successfully
Result
The computed control output is:
1.44
Industry Application
PID control is used in:
Robotics control
Autonomous vehicles
Industrial automation
Process control
Companies like Tesla, Inc. use this in:
Autopilot systems
Vehicle control
Real-time feedback systems
Conclusion
Proportional control is a fundamental part of PID systems, enabling quick response to errors and improving system stability.
