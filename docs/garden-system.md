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