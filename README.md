# Toggling of LED(Light Emitting Diode)
**Objective :** \
To understand the basic working of the Arduino microcontroller and to learn about how to make connections using jumper wires. \
**Outcomes&Learning :** \
I have learned to make connections using the arduino uno microcontroller and jumper wires. \
**Components Required :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-07%20115719.png?raw=true) \
**Circuit :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-07%20115544.png?raw=true)
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-07%20115208.png?raw=true) \
**Code :** \
To execute the expected outcome \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-08-05%20220803.png?raw=true) \
**Code Explanation :** \
**Setup()** special function in the arduino that enables board to set the connections. \
**pinMode(7,OUTPUT)** this function describes that the connection is made with the digital pin 7 and the output is recorded from the pin 7. \
**loop()** function that continously repeat it's execution. \
**digitalWrite(7,HIGH)** function that provides high voltage output to the pin 7. \
delay(1000) function that stops the program for  1000ms i.e 1 sec. \
**digitalWrite(7,LOW)** function that provides low voltage output to the pin 7. \
delay(1000) stops the program for 1 sec .
# Traffic Light 
**Objective :** \
To understand the applications of the toggling of the LED. \
**Outcomes&Learnings :** \
I have learned the several application of the toggling of the LED's one of them is using them in the traffic signals. \
**Components Required :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-08%20215916.png?raw=true)
**Circuit :** 
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-08%20215943.png?raw=true)
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-08%20220000.png?raw=true)
**Code :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-07-08%20220017.png?raw=true) \
**Code Explanation :** \
**Setup()** special function in the arduino that enables the connection of the board. \
**pinMode(7,OUTPUT)** The pin is connected to the 7,4,and 2 from these pins the output voltage is taken. \
**loop ()** function that continously execute the code. \
**digitalWrite(7, HIGH)** This is to ON the red light. \
**delay(5000)** stops program for 5 sec. \
**digitalWrite(7, LOW)** to OFF the red light.\
**digitalWrite(4, HIGH)** to ON the yellow light. \
**delay(1000)** stops program for 1 sec.\
**digitalWrite(4, LOW)** to OFF yellow light. \
**digitalWrite(2, HIGH)** to ON green light.\
**delay(5000)** stops program for 5 sec.\
**digitalWrite(2, LOW)** to OFF the green light.\
Again the same set of program is repeated.
