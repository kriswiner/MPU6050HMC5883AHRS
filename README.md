MPU6050HMC5883AHRS
==================

9 DoF sensor fusion with AHRS output for MPU-6050 gyro/accel + HMC5883 magnetometer sensor

 Demonstrate MPU-6050 basic functionality including initialization, accelerometer trimming, sleep mode functionality as well as
 parameterizing the register addresses. Added display functions to allow display to on-breadboard monitor. 
 No DMP use. We just want to get out the accelerations, temperature, and gyro readings.
 Added the HMC5883L magnetometer for true 9 DoF sensor fusion using the open-source Madgwick and Mahony quaternion filtering 
 algorithms. Out put as Yaw, Pitch, and Roll with absolute orientation to fixed true North (magnetic North plus declination)
 and Down (gravity). Easy 9 DoF sensor fusion with inexpensive and ubiquitous sensors.
 
 Runs on 3.3 V 8 MHz Pro Mini at ~150 Hz filter update rate.

A discussion of the use and limitations of this sensor and sensor fusion in general is found here: https://github.com/kriswiner/MPU-6050/wiki/Affordable-9-DoF-Sensor-Fusion.
