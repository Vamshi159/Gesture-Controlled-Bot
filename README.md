 Gesture-Controlled-Bot

* This is a Hand gesture controlled Bot using Arduino. This is based on Arduino Nano, MPU6050, RF Transmitter-Receiver pair and L293D Motor Driver

* The project is based on wireless communication, where the data from the hand gestures is transmitted to the robot with the help of transmitter and receiver pair

* Firstly we get the data from the MPU6050 with the help of Arduino and Arduino sends the data to Encoder IC which encodes the data and sends it to the RF transmitter

* As soon as RF transmitter receives the data it sends the data through RF communication to the RF receiver

* Finally the data received by RF receiver is decoded by the Decoder IC and the data is send to the Motor driver IC which controls the wheel motors of the Bot.

- The components used are
  * Arduino Nano
  * RF Transmitter(434MHz)
  * HT-12E Encoder IC
  * MPU6050 - Accelorometer/Gyroscope Sensor
  * 750K ohm resistor
  * L293D Motor Driver IC
  * HT- 12D Decoder IC
  * RF Receiver(434MHz)
  * 33K and 330K Ohm resistors
  * Geared Motors and robot chasis
  
