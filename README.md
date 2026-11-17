# Matlab_Robotics1
self balancing robot in matlab
This project models and controls a 3D two-wheeled self-balancing robot in MATLAB and Simulink using Simscape Multibody.
Modeled as an inverted pendulum on a cart, the system consists of a wheeled base connected via a Prismatic Joint (for horizontal movement) and a multi-plate upper chassis connected via a Revolute Joint (for tilting). A PID controller continuously measures the chassis tilt angle and applies corrective horizontal forces to the cart, stabilizing the robot upright against external pushes and enabling controlled forward motion at a target lean angle.
