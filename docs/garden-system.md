# Architecture 
+ Sensors -> MCU Board + Network module -> Gateway -> Server 
+ Sensor 
    + Sensor device to measure the garden env and condition 
    + Capture physical object to digital form -> computing and processing 
+ MCU board with network module 
    + Process data acquired from sensors.
    + Send sensor data to a server for further computation
    + MCU board should be attached to a network module - Ethernet or wireless 
+ Gateway : 
    + If have to modify protocol format 
    + If a network module has the ability to delivery data over a primitive protocol, the functioning of the gateway is necessary 
    + Gateway can translate one protocol format to another protocol format 
+ Server 
    + Center computation 
    + Server have high end hardware 

+ You can use Raspberry Pi or BeangleBoard 

+ Open Garden shield for Arduino 
    + Open Garden shield for Arduino is manufactured by Cooking Hacks 
    + Provide : I/O connectors for gardening and farming sensors 
    + Includes RF module with 433 Mhz frequency 
    + Sensors and tool 
    + Indoor kit , outdoor kit, Hydroponics kit 
+ Grove Smart plant care kit for Arduino 
    + Connect board to various sensors and actuator devices 
    + temperature, humidity, soild moisture, illumination intensity sensor 
+ EcoDuino 
    + Garden kit from DFRobot 
    + MCU board and sensor 
    + RF module breakout in an XBee breakout model 
    + Enable board to communicate with other platforms 
    + Kit have sensors for soil moisture, temparature, and humidity
+ Sensor devices for a smart gardening system : 
    + Soil moisture sensor
        + To read soil moisture values, we can use analog I/O- SketchAPI 
            + analogRead 
            + analogWrite() : write anolog data to an analog pin on Arduino 
+ Connect Arduino board to the SparkFun Soil Moisture sensor - Wiring used 
    + VCC is connnected to 5V on the Arduino 
    + GND - GND on Arduino 
    + SIG - A0 on the Arduino 
+ Open Arduino software - download the tool 
    + Write Sketch program - Create this script 
+ Temparature and Huminity sensor 
    + Use DHRT22 - DHRT 11 - sensor 
    + Single wire digital interface 
    + Connect DHT22 module to the Arduino 
    + Access the DHT 22 on the Arduino - use DHT sensor lib - from Adafruit 
+ Watering your garden and farm    
    + Pumps - Arduino - RaspBerry Pi 
+ Build a smart gardening system 
    + PID controller - manage all inputs from our sensors - decision system 
    + Sensor -> MCU board with wireless module - Relay - Watering system - A computer with decision support system 
    + You can replace MCU board and computer with a mini computer such as RaspBerry Pi  
+ PID controller 
    + Proportional = integral - derivative - PID control
    + Read sensor - compute the desired actuator output - 
+ Send data from Arduino to the server 
    + Models have built in Wi Fi that can connect and send data to a server 
    + HTTP or MQTT proto - 

# Projects 
## A smart Parking System
+ Using Arduino and Raspberry Pi boards 
+ Introduce smart parking system 
+ Sensor devices 
    + Ultrasonic sensor - HC SR 04 : measure range between itself and an object 
    + ultrasonic transitter - control circuit 
    + 4 pins - VCC- GND - Echo - Trigger 
    + Used it with Arduino, Raspberry Pi, other IoT boards 
    + Develop a simple app to access HC Sr 04 on an Arduino board 
        + VCC connect to Arduino 5V 
        + GND connect to Arduino GND 
        + Echo - 
        + Trigger
    + PIR monitor sensor 
        + Object movement 
        + PIR motion sensor 
    + Hall Effect sensor 
        + Magnet 
    + Camera 
        + Image processing - machine learning 
        + Pi Camera - V2  
    + Ultrasonic sensor 
    + Vehicle plate number detection 
        + Open ALPR - 
+ Detection 
+ Parking management system 
    + Sensors - connect to central system - 
        + Web application - Restful - MQTT - Database 
        + Browser/ Mobile app - web application - Restful - MQTT - Core parking system application - database - sensor 
        + sensor - connect to board system - Arduino - Raspberry pi - sensor will detect 
        + put a camera - and sensors on each floor in the building - build gates with the sensor - deploy 



## Vending machine 
+ Vending machine - automate machine that sells products  - central control machine - detect coins for payment - build user interaction - design database model - build vending machine 
+ Machine cabinet - Product storage - Central processor machine - Payment system - User experience 
+ Vending Machine system : core vending system - back end system - User input - user selection - product delivery - refund - 
+ Raspberry pi - arduino : central processing machine - GPIO for sensor and actuator devices 
+ Central control machine : FPGA to control all processes and transaction - AMS sensit 2PC board 
+ Simple vending machien - Arduino board = control unit in your vending machine - digital - analog I/O pins - attach to the machine - extends I/O pins using additional ICs
+ Raspberry PI = control unit - for vending machine - control unit - computer - low end feature - desktop lib : OpenCV - with RP = image processing and detection 
+ Detect 
    + coin weight : sensor Gravity - DFRobot - weight sensor - use directly with Arduino board - HX711 IC to measure object weight - SparkFun - module - connect Gravity to Arduino through analog inputs - Sensor DOUT pin - Sensor SCK pin 
    + Write Sketch program - Arduino IDE - write the sketch program 
    + Coins using optical sensing : 
        + Camera - coin model - connect your camera - embedded system - Raspberry Pi - image processing - install OpenCv - Python app to detect coins - 
+ Display interface 
    + Arduino and RP - LCD 
    + Input interface - module - get input from user - Membrance matrix keypad - Adafruit - Keypad lib - arduino - 
+ Design database model : Product - Transaction - Vending 
+ Building Vending machine 
    + Finite state machine - 
    + Input from user - RP = central unit for the vending machine - Control input from user - handle product selection processing - monitor - replay modules to communicate with them- 


## Smart digital advertising dashboard 
+ Digital signage platform 
+ Smart digital advertising system 
+ Human presence 
+ Display and delivery content 
+ 1Play : digital signage system - RP - Pi Zero and Pi 1,2,3 - images, videos, RTSP video streaming - Content - cloud server 
+ Screenly : platform - based web application 
+ Display - Ads System + Local Database = OS 
+ Deploy multiple ad servers at several location  - central database - ad content - push to each local ad server 
+ Connect between server - and local ad server - estimate network bandwidth capacity - push to the local server at certain periods 