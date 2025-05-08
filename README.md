# Effective-Security-Surveillance-Cam-Robot
We will discuss how to control a robot-controlled car utilizing a Wi-Fi module and a mobile phone in this project. For spying purposes, a new version of a wirelessly operated car has been proposed. This robot is a portable espionage robot with a wireless communication system. A camera, motor drivers, batteries, and two moving wheels make up the spy robot. The ESP32-CAM module has an ESP32-S processor, an OV2640 camera, and a microSD card slot. Images captured by the camera can be stored on a MicroSD card slot. The HTTP communication protocol will be utilised to receive video camera via a web browser in this case. The web page will also have buttons for moving the car left, right, forward, and backward.

**Chapter 01: Introduction**

**1.1. Introduction**

With the rapid growth of information technology, a range of video surveillance systems have become commonplace in daily life for surveillance and security purposes. Closed-circuit television (CCTV), often known as video surveillance, is an example of how video cameras send video signals to a limited number of monitors. When CCTV was initially introduced, its low quality and high installation costs restricted its use. Another common example is the dashboard camera. In the event of a car accident or vandalism, dashboard cameras can provide video proof. On the other hand, as a car dashboard camera is installed inside a car, it can record while the car is moving. To perform car tracking efficiently, these two types of devices should be considered together. In the case of CCTV, as its location is fixed and its hardware performance is superb, it is highly effective for the monitoring of car movements in a predefined area. 

**1.2. Background**

Technology has brought a dynamic and tremendous modification in AI and automation field that ranges in all kinds of areas. Surveillance is the process of systematic observation or direction maintained over an individual, group, etc. particularly one in custody or beneath suspicion. Therefore, surveillance is needed within the areas like border areas, public places, offices and in Industries. It is mainly used for observation activities. The act of Surveillance can be performed each indoor also as in outside areas by humans or with the help of embedded systems like robots and alternative automation devices. A robot is nothing however an automatic electronic machine that can play programmed activities therefore replacing human work, providing extremely correct results, and simply overcoming the constraints of citizenry

**1.3. Project Objectives**

The main objective of this project is:

• To design a proper prototype of the robotic car

• To make the car to move in in four directions

• To control the prototype using ESP-32 cam and Wi-fi module

• Receive directions and information via Wi-Fi from Android mobile phone

• Receive and transmit information from recondite remote place.

**1.4. Scope**

This proposed work is based on the field of robotics in IoT. This robotic car can be used in various filed like robotics, pollution monitoring, automatic obstacle detection, etc. This work can be used in the delivery of products as well. As we know, nowadays corona is spreading in the whole world and the world is facing a situation of lockdown. So, this robotic car can be used in the delivery of products.

**1.5. Project Management**

![image](https://github.com/user-attachments/assets/e32e611d-e0fd-461f-baec-a04f4dd90f10)

Figure 1. Model of phases in project management.

**1.6. Overview and Benefits**

Autonomous security robots can move in complex environments, detecting and reporting anomalies in the environment. Their sensors and cameras allow them not to lose their balance, even when moving through complex terrain. With improvements in 5G networks, robots can traverse even larger and more complex areas. Security robots can help enhance the capabilities of security professionals. Far from replacing them, they can help them with other more boring and time-consuming tasks, so they can focus on more important tasks. 

**1.7. Organization of the Report**

The report is organised into the following chapters. Each chapter is unique on its own and is described with necessary theory to comprehend it.
Chapter 2 deals with background survey and review, Chapter 3 has the description of the theoretical aspects that has been acquired to commence the project work.

**Chapter 02: Background Review & Survey**

**2.1. Related Works**

The world of control is an exciting field that has exploded with new technologies where the Internet of Things vision becomes a reality. Robotics is a technology for making machine which can do more than one task simultaneously, repeatedly. A robotic machine is a mechanical and virtual agent that is operated by computer and electronic power. Nowadays, robots are doing a dangerous task which a person cannot do i.e., survival in a hazardous environment. Robot cars controlled by mobile phones will make work easier as the robot car can move from one position to another position in the touch of a mobile screen. The work in this field is enhancing day by day. A method for controlling a car from an android phone is already proposed in 2016. The robot car can be controlled using Wi-Fi, through an SMS as well. The existing method used Arduino as the main part of the model. It is increased the efficiency to control the model with the Node MCU module. In this filed, many robots have been developed for different requirements. Ultrasonic sensors and Bluetooth technology had been used for obstacle detection. A robot had been developed for the military area to detect metal, to detect explosive things, and to view surroundings view from an android mobile camera. IoT robots can be used in disaster management to save many lives. In this paper; the authors proposed an AI based IoT robot car from android mobile phone using wireless technology. The authors used the BLYNK app for sending instructions to the motor driver. A robot using socket programming had also been developed; this is the way of controlling a surveillance robot from android phones developed in socket programming. This paper presents a way of controlling a robot car from android phones using an Arduino, NodeMCU Wi-Fi module, and embedded C programming

**Chapter 03: Theoretical Aspects**

**3.1. Internet of Things (IoT)**

The Internet of things (IoT) describes physical objects (or groups of such objects) with sensors, processing ability, software and other technologies that connect and exchange data with other devices and systems over the Internet or other communications networks. Internet of things has been considered a misnomer because devices do not need to be connected to the public internet, they only need to be connected to a network, and be individually addressable.

**3.2. Features of IoT**

a) Intelligence

b) Connectivity

c) Dynamic Nature

d) Enormous Scale

e) Sensing

f) Heterogeneity

g) Security

**3.3. Advantages of IoT**

a) Communication

b) Automation and Control

c) Information

d) Monitoring

**3.4. Disadvantages of IoT**

a) Compatibility

b) Complexity

c) Privacy/Security

d) Safety

**3.5. Application areas of IoT**

a) Consumers

b) Home automation

c) Medical and health care

**3.6. IOT Technologies and Protocols**

a) Bluetooth

b) Zigbee

c) Z-Wave

d) Wi-Fi

e) Cellular

f) NFC

g) LoRaWAN

**3.7. Project Layout**

![image](https://github.com/user-attachments/assets/800719c2-9137-419d-a277-0980adb09d67)

Figure 2. Layout of project module

*3.7.1. Brief Description*

In project layout we have two parts:

• Hardware module

• Software module

In hardware module we have 4 parts:

• SG90 servo motor

• L298 Motor driver

• Chassis and wheels

• ESP-32 Cam

It describes what are the main hardware components in this project which can be performed practically. We need 4x wheels & DC motors. And one servo motor formovement of camera up and down.

In software module we need only:

• Processing IDE
For designing the car and how to implement and to what implement we logically written the code in the Arduino IDE and uploaded it on the board.

**Chapter 04: Hardware Requirements**

**4.1. ESP-32-cam**

The ESP32-CAM is a small size, low power consumption camera module based on ESP32. It comes with an OV2640 camera and provides onboard TF card slot.
The ESP32-CAM can be widely used in intelligent IoT applications such as wireless video monitoring, WiFi image upload, QR identification, and so on.
The ESP32-CAM suit for IOT applications such as:

• Smart home devices image upload

• Wireless monitoring

• Intelligent agriculture

• QR wireless identification

• facial recognition

*4.1.1. Features*

• WIFI module: ESP-32S

• Processor: ESP32-D0WD

• Built-in Flash: 32Mbit

• RAM: Internal 512KB + External 4M PSRAM

• Antenna: Onboard PCB antenna

• WiFi protocol: IEEE 802.11 b/g/n/e/i

• Bluetooth: Bluetooth 4.2 BR/EDR and BLE

• WIFI mode: Station / SoftAP / SoftAP+Station

• Security: WPA/WPA2/WPA2-Enterprise/WPS

• Output image format: JPEG (OV2640 support only), BMP, GRAYSCALE

• Supported TF card: up to 4G

• Peripheral interface: UART/SPI/I2C/PWM

• IO port: 9

• UART baudrate rate: default 115200bps

• Power supply: 5V

• Operating temperature: -20 °C ~ 85 °C

• Storage environment: -40 °C ~ 90 °C, <90%RH

*4.1.2. Pin Configuration*

![image](https://github.com/user-attachments/assets/245bacbc-254e-4943-89e2-b9f6573215a0)

![image](https://github.com/user-attachments/assets/2459519b-5611-4f4e-b56c-25f5ce0fffc4)

**4.2. DC Motor**
A DC motor is an electrical machine that converts electrical energy into mechanical energy. In a DC motor, the input electrical energy is the direct current which is transformed into the mechanical rotation. A DC motor is defined as a class of electrical motors that convert direct current electrical energy into mechanical energy.

**4.3. Servo motor (SG90)**
SG90 is a popular micro servo motor commonly used in hobbyist and DIY projects. It is a small, low-cost servo motor that can rotate 180 degrees with a maximum torque of 1.8 kg-cm. It operates at 4.8-6V and has a weight of approximately 9 grams, making it ideal for small-scale robotics and model control applications.

*4.3.1. Features*

• Torque: 2.0kg/cm(4.8V), 2.2kg/cm(6V)

• Speed: 0.09s/60°(4.8V), 0.08s/60°(6V)

• Rotate angle: 180°

• Operating voltage: 4.8 ~ 6V

• Gear: plastic

• Dead band: 7μs

• Weight: 10.5g

• Dimension: 22.8mm × 12.2mm × 28.5mm

*4.3.2. Pin Configuration*

![image](https://github.com/user-attachments/assets/91b1ec71-523a-466e-ab8d-4d051264fa72)
![image](https://github.com/user-attachments/assets/5f5b533f-3581-408a-8ea6-26128312f83d)

**4.4. L298N DC Motor Driver**
The L298N chip contains two standard H-bridges capable of driving a pair of DC motors, making it ideal for building a two-wheeled robotic platform.
The L298N motor driver has a supply range of 5V to 35V and is capable of 2A continuous current per channel, so it works very well with most of our DC motors.

*4.4.1. Features*

• Driver Model: L298N 2A

• Driver Chip: Double H Bridge L298N

• Motor Supply Voltage (Maximum): 46V

• Motor Supply Current (Maximum): 2A

• Logic Voltage: 5V

• Driver Voltage: 5-35V

• Driver Current:2A

• Logical Current:0-36mA

• Maximum Power (W): 25W

• Current Sense for each motor

• Heatsink for better performance

• Power-On LED indicator

*4.4.2. Pin Configuration*

![image](https://github.com/user-attachments/assets/424bfa60-c70b-4567-a790-1bb0c45f8a5a)

**4.5. Block diagram of the proposed system**

![image](https://github.com/user-attachments/assets/3797d34e-c0e5-43b7-aeb8-5386276eccd7)

*4.5.1. Working of the system*

Any robot's structure, or body, on which its whole control circuits and actuators are to be attached, is a basic requirement. The fundamental goal of our design is to move the device in response to the button. As a result, we created a simple robot that can go forward, backward, left, and right by simply pressing a button. As the ESP32-CAM lacks a USB port, an Arduino UNO board is required to upload the code. The ESP32's VCC and GND pins are wired to the FTDI board's VCC and GND pins. The ESP32's Tx and Rx are linked to the FTDI board's Rx and Tx. Through the L298N module, two DC motors are connected to ESP32. The IO4, IO2, IO14, and IO15 pins of the ESP32 are connected to the module pins.
The surveillance bot ESP32-CAM module has an ESP32-S processor, an OV2640 camera, and a microSD card slot. Images captured by the camera can be stored on a MicroSD card slot. The HTTP communication protocol will be utilised to receive video streaming from the OV2640 camera via a web browser in this case. As indicated in the image above, the web page will also feature buttons to move the car in the Left, Right, Forward, and Reverse directions.

*4.5.2. Circuit Diagram*

![image](https://github.com/user-attachments/assets/0869d7ef-4e68-448d-ab7f-1cd9f7f41dde)

**Chapter 05: Software Requirements**

**5.1. Arduino IDE (Embedded C / C++)**

The Arduino IDE is an open-source software, which is used to write and upload code to the Arduino boards. The IDE application is suitable for different operating systems such as Windows, Mac OS X, and Linux. It supports the programming languages C and C++. Here, IDE stands for Integrated Development Environment.

**5.2. Logic and Flowchart**

![image](https://github.com/user-attachments/assets/dbd85820-226c-4657-a3f1-1ab997478fec)

**Chapter 06: Project development & Testing Aspects**

![image](https://github.com/user-attachments/assets/7fb0d5d8-5f1a-48d9-99e4-cbca9166390e)
Connecting wires
![image](https://github.com/user-attachments/assets/3467d353-ade8-4676-9d20-d84425739e7d)
DC motors
![image](https://github.com/user-attachments/assets/70b24001-06ec-4c8b-b39a-d16dfbe27d24)
Wheels
![image](https://github.com/user-attachments/assets/6760b74d-2940-4362-9442-b798177f961f)
Chassis
![image](https://github.com/user-attachments/assets/1550cb21-9596-4d31-ba9c-60666f8c7952)
ESP-32 CAM
![image](https://github.com/user-attachments/assets/45751d97-ab5e-4473-919b-bad89d17d805)
L298N motor driver
![image](https://github.com/user-attachments/assets/d0bd5bc5-2ed1-450e-a939-4b418de8313c)
Screws, Nuts and bolts
![image](https://github.com/user-attachments/assets/0e9bc544-4d32-4749-a1ab-40f3dd96255f)
![image](https://github.com/user-attachments/assets/e0487c9f-5533-4205-944a-683acf9be44e)
![image](https://github.com/user-attachments/assets/009d08e2-7a80-46bf-8a18-5fb8c06685a6)
![image](https://github.com/user-attachments/assets/591a9edc-9a9b-4f04-a3e3-dab1427de6ae)
![image](https://github.com/user-attachments/assets/25666223-ba42-4905-9fe0-25958e08e4fb)
![image](https://github.com/user-attachments/assets/7a9431c5-6d79-4719-934e-498ac76337c2)
![image](https://github.com/user-attachments/assets/6dc5ee96-99c3-4bb4-9995-c2f1e4e26d41)
![image](https://github.com/user-attachments/assets/832ae392-6654-4efd-8b2a-f9eb2c82871d)
Final car system
![image](https://github.com/user-attachments/assets/b2d1f940-9c16-46ce-9cfa-a69341b55751)

**Chapter 07: Conclusion & Future Scope**
**7.1. Result**

The live video captured by the camera will be sent to the android application by which we will decide the movement of our vehicle.

**7.2. Conclusion**

In this work, the framework for creating a automaton for police work purpose is proposed. It overcomes the matter of restricted vary police work by mistreatment the concept of IOT. The automaton will be controlled with the assistance of mobile manually. Our projected automaton is tiny in size so maneuvering into space wherever human access is not possible. Wireless technology is one in every of the foremost integral technologies within the natural philosophy field. This technology is employed is a supreme a part of police work act. This provides extremely economical and a price effective automaton that replaces human work and reduces human labor and performing observance works during a well effective manner

**7.3. Limitations**

It has limited distance. Existing systems use robots that have restricted vary of communication. Cyber security effects on robot cars. The security behind self-driving cars would be the major obstacle, especially the hackers’ effect on the vehicle’s software and control its operation.

**7.4. Further Enhancement and Future Scope**

• In further development the distance range may be to 1 kilometer.

• The number of sensors may be increased to get more data.

• Machine learning using the json and XML file for predicting human

• Condition and weather condition can be developed.

Regularly Patrolling the streets to keep people safe and assist in notifying the authorities as soon as possible. There is a very slim probability of receiving inaccurate or biased information. Identifying, collecting, and rapidly submitting information to authorities if it matches any person's criminal history in its criminal database. For instance, if some criminal is on the run, the bot can send police a message with its last location

**References**

• https://www.youtube.com/watch?v=pD2VFKUlWC8

• https://ijarsct.co.in/Paper4779.pdf

• https://www.ijert.org/research/surveillance-car-bot-future-of-surveillance-car-bot-IJERTV10IS100113.pdf

• https://www.ijert.org/surveillance-car-bot-future-of-surveillance-car-bot
