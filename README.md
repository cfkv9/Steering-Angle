# Steering-Angle

In the past we have used a custom steering angle sensor(More documentation below). I have never used it. I have been told by some that the sensor was fine and did not have to much error, but others have said it has terrible accuracy. So I would like to look into how well the old sensor worked. And if improvments need to be made or even go to an entirely different system. The second issue is that the connector was way to big. A redesign of the board will be nesisary if we keep with the same chip. 


Steering DAQ

Steering Angle
	An important sensor for the steering system is the steering angle sensor. In the recent history of the team, not much has been done with the data from this sensor, however it is actually very valuable data for calculating dynamic performance of the car as well as useful for driver and track comparisons. In the past a gear-style sensor has been used. This sensor is typically mounted near the bottom of the steering column with a gear on the column. This is a very bulky sensor and tends to wear out with the team experiencing gear failure when using plastic gears. 
To improve this sensor, the team has developed a custom steering angle sensor that uses a magnetic rotary position sensor (AS5045) and a magnet on the bottom of the steering column. This sensor gives very clean and high-resolution data. There are some things to be aware of with this sensor. The sensor gives a 0-5V reading. It is important to make sure that the transition from 5V back to 0V in the sensor is not occurring during the usable range of the steering. The steering typically only rotates about 230 degrees. To adjust the 0V position all that needs to be done is rotate the magnet on the steering column. 
	The steering angle sensor mounts right underneath the steering column and its magnet with aluminum spacers to make sure the sensor is mounted the correct distance from the magnet. One issue that was encountered was the size of the connector on the board of the sensor. The orientation and type of connector on the board did not fit well underneath the steering column so the wires had to be directly soldered to the board, which is not ideal. 
