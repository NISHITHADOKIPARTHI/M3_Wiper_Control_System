# INTRODUCTION:
* Wiper is an essential component that used to wipe raindrops or any water from the vehicle’s windscreen. The previous system used to activate the wiper manually and the process of pulling up the wiper is difficult to be handled. Thus, this system is proposed to solve these problems. The objectives of this project are to upgrade the older cars system by providing automatic wiping system, to improve the system by using sensor with actuator and to design a basic program that will fully operate with the system. The concept of this proposed wiper system is similar with other existing conventional wiper. In spite of removing water from windscreen, this system also will be upgraded to an automatic control system by using a Peripheral Interface Controller (PIC) 16F877A controller and water sensor. As the conclusion for the project, the results shows all the aim objectives are successfully achieved. The wiper system was well functionally according the water condition from the outside of a car. This project showed a contribution on the design of the automatic wiper system for the future research in this same field. It is recommended that the system to have a study on the wiper material that been used to make a wiper because the driver at hot and climate country are facing the problems regards to the wiper material.

# COMPONENTS AND SUPPLIES:

 1. STM32F407 Discovery Board
 2. LEDs
 3. Push Button
 4. Resistors
 5. Power Supply

# Description
 
   1. STM32F407VG
 
 * The STM32F405xx and STM32F407xx family is based on the high-performance Arm® Cortex®-M4 32-bit RISC core operating at a frequency of up to 168 MHz. The Cortex-M4 core features a Floating point unit (FPU) single precision which supports all Arm single-precision data-processing instructions and data types. It also implements a full set of DSP instructions and a memory protection unit (MPU) which enhances application security. The STM32F405xx and STM32F407xx family incorporates high-speed embedded

  2. LED
  
  * A light-emitting diode (LED) is a semiconductor light source that emits light when current flows through it. Electrons in the semiconductor recombine with electron holes, releasing energy in the form of photons

   3. Push Button
  
  * Push buttons can be explained as simple power controlling switches of a machine or appliance. These are generally metal or thermoplastic switches that are    intended to grant easy access to the user.
  
   4. Resistors
  
  * A resistor controls the flow of the electrical current within a circuit. Resistors are made from materials like copper or carbon, which make it difficult for the electrical charges to flow through a circuit.
  
   5. Power Supply
  
  * A power supply is an electronic circuit that converts the voltage of an alternating current (AC) into a direct current (DC) voltage. It is basically consisting of the following elements: transformer, rectifier, filter and regulator circuits.

# ADVANTAGES:
* Rain sensors store water during rain events, allowing it to be available throughout the summer and winter.
* It is quite simple to use.
* As a consequence, rain sensor-based equipment like vehicle wipers and irrigation systems last longer since they only work when needed.
* Individual rain sensors are fairly inexpensive.
* Rain sensor-based systems are extremely simple to install.
* To save money during wet seasons, turn off the irrigation system. Electricity bills are lowered as a consequence.

# DISADVANTAGES:
* Rain sensors must make a decision within a few minutes to avoid erroneous detection of rain.
* The entire system cost rises when more components, including a rain sensor, are required.
* When water falls squarely on the rain sensor, the mechanism activates.

# Requirements
## High level requirements
| ID | Discription | status |
| --- | --- | --- | 
| HR_01 |	Car is in ACC mode |	Implemented |
| HR_02 |	Car is in Ignition mode |	Implemented |
| HR_03 |	Wiper turned on |	Implemented |
| HR_04 |	Wiper turned off |	Implemented |
## Low level requirements
| ID |	Discription |	status |
| --- | --- | --- | 
| LR_01 |	Button pressed ONCE for two seconds - ON LED RED |	Implemented |
| LR_02 |	Button pressed once again times - OFF LED RED |	Implemented |
| LR_03	|Button pressed two time - ON BLUE,GREEN,ORANGE |	Implemented |
| LR_04 |	Button pressed again for two seconds - OFF ORANGE,GREEN,BLUE |	Implemented |

## 4W's And 1H
## Who
- Everyone who needs to drive safely and with a clear view of the road.
## What
- Wiper Control System for vehicles.
## When
- When you realise the necessity of safety management and begin to take responsibility for your own health while driving in adverse weather.
## Where
- This can be utilised in daily life by the user to assess their safety and lead to better outcomes in life while travelling.
## How
- The position of the wiper is indicated by the LED, which returns to its original position after cleaning the windsheet of the vehicle.

## SWOT ANALYSIS:
## STRENGTH
- Clear visibility
- Single button can manage all commands
- Wiper does not stop in the middle, it goes to its original position.
- Installation is simple
## WEAKNESS
- High cost
- Replacement of wiper is required
## OPPORTUNITIES
- Reducing accidents
## THREATS
- Replaced by modern technology

# Exploring STM32F407 Discovery Board:
![image](https://user-images.githubusercontent.com/101699116/168215005-061df6d3-4596-4639-8eea-13b069ee27cb.png)

This venture gives practically all the fundamental data expected to begin with STM32F407 Discovery Board and furthermore advancement of driver code.
* Hardware Used : STM32F4 DISCOVERY kit, for more information visit: STM32F4 DISCOVERY
* Software Tool : STM32cubeIDE, for more information visit: STM32CubeIDE
* For installation of STM32CubeIDE refer Youtube
* Note : As this microcontroller has many advanced features and the main aim of this project is to get all basic insights, during the driver development only the required functionalities are added and other advanced functionality is not added. I may update the driver and other functionality in the future.
Please find the STM32F4 Discovery User Manual,STM32F4xxx Reference Manual (RM0090) and other related documents inside a folder called Documents. I will be referring to these documents for information such as block diagrams, register details ect.

# OUTPUT IMAGES:
1.user button and hold it for two seconds

![image](https://user-images.githubusercontent.com/101699116/168215381-5ecc8142-9d24-4736-8735-bc312903aa7d.png)

2.WIPER SPEED LOW

![image](https://user-images.githubusercontent.com/101699116/168215423-e3d86028-68c5-47ce-aecc-96c930a879df.png)

3.WIPER SPEED MEDIUM

![image](https://user-images.githubusercontent.com/101699116/168215452-9ec26809-fa7a-445d-a48c-f0a421172afe.png)

4.WIPER SPEED IS HIGH

![image](https://user-images.githubusercontent.com/101699116/168215482-7f1316c6-23bf-4b6a-ad76-59bd2606e306.png)


5.user button is pressed and held for 2 seconds, the red LED is off

![image](https://user-images.githubusercontent.com/101699116/168215572-07fc1962-aa78-46a6-a1e3-71e4326f809d.png)