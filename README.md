# IOT-based-Task1
# Ultrasonic Sensor Distance Detection with LED

## Description
This project uses an HC-SR04 Ultrasonic Sensor and Arduino Uno to measure the distance of an object. The measured distance is displayed on the Serial Monitor, and an LED is controlled based on the detected distance.

- LED ON when the object is within 100 cm.
- LED OFF when the object is farther than 100 cm.

## Components Used
- Arduino Uno
- HC-SR04 Ultrasonic Sensor
- LED
- Jumper Wires

## Pin Connections

| Component | Arduino Pin |
|------------|------------|
| TRIG | D8 |
| ECHO | D7 |
| LED | D13 |
| VCC | 5V |
| GND | GND |

## Working
1. The ultrasonic sensor sends sound waves.
2. The echo signal is received after reflecting from an object.
3. Arduino calculates the distance using the echo time.
4. Distance is displayed on the Serial Monitor.
5. If the distance is less than or equal to 100 cm, the LED turns ON.
6. Otherwise, the LED turns OFF.

## Formula Used

Distance (cm) = (Duration × 0.034) / 2

## Features
- Real-time distance measurement
- Object detection using ultrasonic sensor
- LED indication for nearby objects
- Serial Monitor distance display

## Demo Video

🎥 Watch the project demonstration here:

https://github.com/your-username/your-repository/assets/video-link

## Author
Kanishka Tiwari
Dayalbagh Educational Institute
