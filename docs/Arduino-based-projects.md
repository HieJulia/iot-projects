# IoT projects 
+ Sensor : sense physical values - metadata 
+ Actuator : actions - based on commands it receives from the Internet 
+ Controller : device that provides app intelligence to the Internet 
+ Cameara : device that publishes a camera through which you will take pictures 
+ Bridge : device - acts as bridge between different proto 
+ RP
+ Clayster lib 
+ Object 
+ Interface the General purpose I/O pins 
+ Circuit diagram 
+ Hardware interface 
+ Interoperability IoT 
+ Data persistence using object database 

### Create the sensor project 
+ Set up basic structure of console application 
+ Config hardware and learn to sample sensor values and maintain a useful historical record 
+ Add HTTP server capabilities - web resource to the project - publish sensor values collected to the Internet 
+ Handle persistence of sampled data in the sensor 
+ Add security layer 
+ Req/Res pattern - Http - send events from the server - > to the client 
+ RP 
    + Model B : SD card Raspbian OS 
    + Config network access - including Wi-Fi 
    + Remote PC - normal working laptop 
    + Exe files - deployed to the RP - boards - exe - run on .NET 
+ Clayster lib 
+ Hardware : 
    + measure things 
        + light sensor - analog sensor - connect to 4 channel - analog - to - digital converter - connect to bus - that we will connect to the standard GPIO pins for I2 C 
        + I2C bus : permit communication with multiple circuits - using sync communication - employs a Serial clock line -and Serial data line pin- communicate with integrate circuits 
        + Temparature sensor - connects directly to the same I2C bus - 
        + SCL and SDA pins - 
        + Infrared motion detector - Parallax PIR sensor - digital input 
        + Add 4 LED to the board - show HTTP 
        + Pins - control the LEDs  - hardware of the prototype board 
        + Circuit diagram 
+ Interact with hardware 
    + Create console app - in Xamarin = enable event logging - compile - deploy - exe the code on RP 
    + Interaction with hardware : digital output - input -device connect to I2C bus - communicate with the static class 
    + constructor - init the corresponding hardware resource - methods - properties to interact with the resource - 
+ Interface the hardware 
+ Internal representation of sensor 
+ Persist data : object database 
+ External representation of sensor values - interchange of sensor data- XML - data - time - 
+ Export sensor data - test method - export some sensor data to XML 
+ Create the actuator project 
    + automation - IoT = actuator - 
    + sensor - sense physical magnitudes or events 
    + actuator = control events - act 
    + Create simpel actuator - run on RP - 8 digital outputs - one alarm output 
    + Hardware - 8 digital outputs and one alarm output 
        + digital output - connection resistor - red LED  
        + alarm output : connect to a speaker 
        + circuit diagram 
    + Create a controller 
        + sensor - controller - LEDs controller 
        + Represent sensor values 
        + Parse sensor data 
        + Calculating control states
    + Create a camera : 
        + Hardware 
        + Access the serial port on RP 
        + Interface the hardware
        + Create persistent default settings 
        + Add config properties 
        + Persist the settings 

