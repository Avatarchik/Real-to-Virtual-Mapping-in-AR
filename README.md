# Real-to-Virtual-Mapping-in-AR

This application was made to understand how accelerometer and gyroscope readings can be used to detect and object in an augmented environment.

Detecting a 2D real object and providing it's attributes to a virtual object. Created using Unity, C#, C++, OpenCV, Python

Module 0
The device camera is caliberated and a camera calibration matrix is generated.

Module 1
A colored 2D object is stuck to an Android smartphone. The phone is connected to the system for accelerometer and gyroscope readings. The camera in the system detects the centeroid of this object from OpenCV script.

A virtual object is created in the 3D environment which takes the color of the described object and performs motion according to the smartphone readings.

Module 2

The camera shuts and the centeroid of the object is detected only using the accelerometer and gyroscope readings.

Tools: Unity, C#, OpenCV, C++, Python