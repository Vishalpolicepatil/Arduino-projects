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
# ADC (ANALOG TO DIGITAL CONVERTER)
**Objective :** \
To understand the working of the ADC by using 10 bit resolution Arduino Microcontroller. \
**Outcomes&Learning :** \
I have learned the basic concepts of the Arduino when it is used as the analog to digital converter. \
**Components Required :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-08-15%20120101.png?raw=true) \
**Circuit :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-08-15%20120024.png?raw=true) \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-08-15%20120041.png?raw=true) \
**Code :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-08-15%20120144.png?raw=true) \
**Output :** \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/Screenshot%202025-08-15%20120311.png?raw=true) \
**Explanation :** \
16F877 AD converter module has maximum 8-analog inputs, except for 28 pin devices that have 5 analog inputs. The result of AD conversion is a 10-bit number. The high and low reference voltages for AD converter are software selectable. AD converter is able to operate even if the device is in sleep condition. There are four registers in AD module, namely, AD result high register (ADRESH), AD result low register (ADFRESL), AD control register 0 (ADCON0) and AD control register 1 (ADCON1). The other registers needed for AD operation are INTCON, PIR1, PIE1, TRISA, PORTA, TRISE, and PORTE. ADCON0 register is as shown in figure below : \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/IMG_20250816_205221.jpg?raw=true) \
ADCON0 allows setting the conversion clock rate, channel selection, to observe the conversion and AD module *ON/OFF* control. ADCON0 is at address 1FH, which is bank 0 of 16F877 register file map. ADC0N1 as shown in the below figure below : \
![alt text](https://github.com/Vishalpolicepatil/Arduino-projects/blob/main/IMG_20250816_205242.jpg?raw=true) \
ADCON1 allows selecting the AD conversion result format(right or left justification), the PORTA and PORTE bits for analog or digital use. ADCON1 is at address 9FH, which is in bank 1.ADCON1 bits 0 to 3 define the analog or digital use of PORTA and PORTE pins. If these bits are 0000, then all PORTA and PORTE pins are configured as all of analog purpose. The corresponding data direction registers must be defined for making PORTA and PORTE pins as inputs.
