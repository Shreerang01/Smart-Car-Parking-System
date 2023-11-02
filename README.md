
# Smart Car Parking System

The rapid urbanization and the increased complexity of city traffic, exacerbated by the post-COVID surge in road usage, have presented a pressing challenge for commuters. With public transportation often falling short of meeting the demands of the growing population, the quest for adequate parking spaces for personal vehicles has become an increasingly arduous and expensive task. In response to this escalating issue, there has been a growing recognition of the need for Internet of Things (IoT)-powered parking systems. These systems offer a solution to mitigate ongoing traffic congestion and the unpredictability of parking space availability. With the proliferation of connected devices, the development of an IoT-based smart parking system has become more accessible. Such infrastructure empowers both drivers and parking facility managers by providing real-time information on available parking slots and current parking fees, enhancing the overall convenience and efficiency of parking in densely populated areas.

This project involves the creation of a Smart Parking System utilizing Arduino, an Ultrasonic sensor, and an LCD display. The primary objective of this system is to furnish users with real-time information regarding parking space availability, thus simplifying the process of parking in congested urban areas. By deploying these technologies, the project aims to contribute to the amelioration of traffic congestion and the optimization of parking resources, aligning with the broader goals of urban mobility enhancement and sustainability.

## Table of Contents

- Installation
- Project Link
- Project Components
- Features
- Getting Started
- Schematic
- Usage
- Contributing
- Acknowledgements
- License
## Installation

```bash
  -Go to my project link below
  -Tinker/Copy it on your account
  -Run Locally by starting Simulation
```
    
## Poject Link

https://www.tinkercad.com/things/bQ4UVy7tytP?sharecode=Evw2C6K6T48zDsKNucTFoY7Ic_wJ1SfwEKVp3haT_p0 
## Project Components
 
 - Arduino Uno R3
 - Ultrasonic Distance Sensor
 - 1 kΩ Resistor
 - 220 kΩ Resistor
 - 250 kΩ Potentiometer
 - LCD 16x2
 - Breadboard




## Features

- **Real-time Updates:** Implement a real-time data refresh mechanism to continuously update parking availability, reducing the delay in displaying changes.

- **User Registration and Profiles:** Allow users to create profiles, enabling them to save their favorite parking locations, receive personalized notifications, and track their parking history.

- **Payment Integration:** Integrate payment gateways to allow users to pay for parking through the mobile app or on-site using digital payment methods, reducing the need for physical payment systems.

- **Reservation System:** Enable users to reserve parking slots in advance, ensuring they have a guaranteed spot when they arrive at the location.

- **Security Features:** Implement security measures to prevent unauthorized access to the system or tampering with the sensors, ensuring the reliability and integrity of the data.

- **Multi-Level Parking Support:** Extend the system to manage multi-level parking facilities and provide information on available slots on each level.
## Getting Started

For Actual Implementation

    1. Clone this repository to your local machine.

    2. Open the `smart_car_parking_mechanism.ino` file using the Arduino IDE.

    3. Upload the code to your Arduino UNO R3.

    4. Wire up the hardware components as per the provided schematic.

    5. Power on your Arduino and interact with the system.

    6. Note the Obeservations
## Schematic

![Schematics](https://github.com/Shreerang01/Smart-Car-Parking-System/assets/113919844/0ed7bf5f-a6db-4d54-9284-48675d62f00a)

## Circuit Diagram

![Screenshot (389)](https://github.com/Shreerang01/Smart-Car-Parking-System/assets/113919844/020b7887-24b9-4d87-ad83-63118a3ae198)


## Usage

- **Monitoring Parking Spaces:**

The LCD display will show the number of free parking slots.
It will also indicate the availability of each slot by displaying slot numbers.
If a slot is free, its number will be displayed; if occupied, it won't be shown.
- **Interpreting the Display:**

The LCD display provides real-time information, allowing users to identify available parking spots quickly.
A count of the free slots is displayed at the top of the screen.
- **Maintenance:**

Ensure that the Ultrasonic sensors have an unobstructed view of the parking spots for accurate readings.
Regularly check the connections and power supply of your Arduino and sensors.



## Contributing

Contributions are always welcome!

See `contributing.md` for ways to get started.

Please adhere to this project's `code of conduct`.

Anyone can contribute to the project by simply tinkering the project to your local machine and adding new features and functionalities and and making it more useful.

## Acknowledgements

 - [Arduino Documentation  ](https://docs.arduino.cc/hardware/uno-rev3 )

 - [Researchgate](https://www.researchgate.net/publication/341870728_Smart_Parking_System_based_on_IOT)

 - [Researchgate ](https://www.researchgate.net/publication/335807455_Smart_Parking_Management_System)

 - [Tomorrow.city](https://tomorrow.city/a/smart-parking )

 - [Smartparking](https://www.smartparking.com/uk)

 - [Airtel](https://www.airtel.in/blog/business/iot-based-smart-parking-system-a-step-towards-building-smart-city/   )
 


 



## License

[MIT](https://choosealicense.com/licenses/mit/)

