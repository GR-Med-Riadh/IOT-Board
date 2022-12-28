# IOT-Board
I would like to share one of my latest PCB designs that I have just received from JLCPCB Foremost, I'd like to thank JLCBCP for their sponsorship, and for supporting young tech enthusiasts, like myself, in creating quality PCBs with great precision.
This PCB is an IOT board, it can be used for many applications : integrating smarter homes, innovating agriculture and Building smarter cities. Using iOT technology, it’s possible to collect data from sensors like : motion sensor, humidity and temperature sensor, gas sensor, and then act according to the data collected by controlling actuators, such as motors. For this project, we use an ESP32 wroom, 32 bits and 12 bits resolutions. It's a dual corps, and it has Bluetooth low energy, Wi-Fi that's help in many iot applications.

A bridge is needed between the sensor and the actuation part of the microcontroller to separate lower and higher voltage devices. For that, we are using an optocoupler that can be activated with 3.3v from the ESP32, once it’s activated, it saturates the transistor that will change the state of our relay, to finally put in action our sensors or actuators. We will also be using, touch pins, these pins are capacitive sensors which can sense variations in anything that holds an electrical charge, like the human skin. Finally, to upload our code into the microcontroller we will be using pins for FTDI.
This PCB is an IoT board that can be used for many applications that include it being integrated into homes to make them smarter, innovating agriculture and building smarter cities. Using IoT technology, it’s possible to collect data from sensors like motion sensors, humidity and temperature sensors and gas sensors, and then act according to the data collected by controlling actuators, such as motors.



For this project, I am using an ESP32 Wroom with 32 bits and 12 bits resolutions. It's a dual corps, and it has Bluetooth low energy and Wi-Fi which is very useful in many IoT applications.

 

A bridge is needed between the sensor and the actuation part of the microcontroller to separate lower and higher voltage devices. For this reason, I am using an optocoupler that can be activated with 3.3v from the ESP32. Once it’s activated, it saturates the transistor that will change the state of the relay, to finally put the sensors or actuators into action.

Touch pins will also be used as they are capacitive sensors which can sense variations in anything that holds an electrical charge, like the human skin. To upload our code into the microcontroller I will be using pins for FTDI.

link of jlcpcb: https://jlcpcb.com/HAR
