This are codes for slaves microcontroller connected to masters via I2C bus. 
The master microcontroller calculates RPM of each motor for maneuvering the robot in specific direction given by user. The RPM value is send to a slave microcontroller. The RPM value acts as a setpoint for PID controller. Each slave controller maintains the rpm at the setpoint calculated by master with the help of PID. 
