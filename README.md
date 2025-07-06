AIM:
To design and implement a real-time monitoring system that uses an MPU6050 (accelerometer + gyroscope) with an OLED display to track and visualize the position and orientation of a moving object in simulation (Wokwi). The system will display live sensor data and calculated orientation angles.

PROBLEM STATEMENT:
Most systems struggle with accurately tracking orientation and motion in three dimensions in real time. We aim to create an affordable, portable solution that uses low-cost sensors and an OLED display to provide immediate feedback on position and orientation, useful for robotics, motion analysis, and wearable tech.

SCOPE OF THE SOLUTION:
Real-time reading of accelerometer and gyroscope data.
Displaying sensor values and computed orientation angles on an SSD1306 OLED.
Simulation demonstrated via Wokwi.
Documentation including flowchart, code, circuit diagram, demo video.

REQUIRED COMPONENTS:
 Hardware	- MPU6050 sensor
- SSD1306 I²C OLED (128×64)
- Arduino UNO (or ESP32)
 Software	- Arduino IDE
- Libraries: Wire, MPU6050, Adafruit_GFX, Adafruit_SSD1306
 Cloud/Online	- Wokwi simulation environment
- GitHub (to host repo)
- Optional: YouTube/Google Drive for demo video

FLOWCHART OF THE CODE:






