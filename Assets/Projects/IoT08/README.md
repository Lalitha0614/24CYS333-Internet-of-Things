# 24CYS333 - Internet of Things
![](https://img.shields.io/badge/Batch-22CYS-lightgreen) ![](https://img.shields.io/badge/UG-blue) ![](https://img.shields.io/badge/Subject-IoT-blue)
<br/>
![](https://img.shields.io/badge/Lecture-2-orange) ![](https://img.shields.io/badge/Practical-3-orange) ![](https://img.shields.io/badge/Credits-3-orange) <br/>

---

## IoT#08 - Smart Vehicle Theft Detection System Using IoT and GPS

| Team members        |
| ------------------- |
| Rahul Shankar V     |
| Aadhithya Sivakumar |
| Hamsini G |

---
### Problem Statement: 
Addressing the issue of wide-spread vehicle theft, by implementing a tamperproof and transparent method of monitoring and communicating with your vehicle and its safety system. The aim is to have a alert and tracking system that tracks the location and condition of the vehicle.

---
### Literature Survey:
- **Existing Solutions:** 
    - IoT-based tracking systems are commonly used to provide real-time vehicle location data. Examples include RFID, GPS, and GSM technologies for communication and tracking. 
    - Cloud platforms and mobile applications to manage and monitor vehicle data. 
    - Protocols: 
	    - MQTT (Message Queuing Telemetry Transport) and HTTP protocols are widely used for IoT communication. 
	    - Data encryption protocols for secure transmission. 
- **Previous Implementations:** 
	- GSM-GPS-based vehicle tracking systems, which send location updates via SMS. 
	- Anti-theft systems using geofencing technology to alert owners when vehicles exit predefined boundaries. 
	- Systems integrated with vehicle immobilization mechanisms (e.g., remotely cutting off fuel or engine). 
- **Challenges:** 
	- Power consumption and reliability of IoT devices. 
	- Dependence on internet connectivity, leading to performance issues in remote areas. 
	- Vulnerabilities to cyberattacks, such as hacking or GPS spoofing.

---
### Associated SDGs: 
The project satisfies 
- **SDG 9** (Industry, Innovation and Infrastructure) 
- **SDG 16** (Peace, Justice and Strong Institutions)

---

### Proposed solution:
The aim of the proposed solution is to have a system that detects unauthorized entry such as a break in and an unauthorized car jack.

##### Case 1 (Normal usage):
* Driver enters the car and closes the door.
* He puts his finger on the fingerprint scanner which authenticates him.
* The car can then continue operating normally.
##### Case 2 (Intruder breaks into car):
* The fingerprint scanner fails and raises alarm.
* An SoS is sent to the phone and its live location is transmitted via the GPS.
* The owner can then inform the police who can track the car.
* At the opportune moment, the owner can disable the engine motors and activate the defense system.
* A panel in the dashboard opens, revealing a 6 shot rubber ball launcher(paintball launcher) that can incapacitate the intruder.
* The owner can be assured that his car is safe.
##### Case 3 (Carjacking):
* The intruder decides to take the car by using some sort of car dragging mechanism so that he steal the car without driving it.
* The accelerometer in the car detects this movement and immediately sounds the alarm and sends SoS to the owners phone number.
* Even if that doesn't trigger, the GPS can be used for geofencing.
* The owner can again wait for the opportune moment to the sound the alarm again for helping the police detect the car

---
### Hardware list
- Raspberry PI Pico Rp2040
- Accelerometer/Gyroscope: MPU6050
- GPS module: Neo-6M GPS or NEO-M8N
- 5V Single Channel Relay Module
- Motors for blocking movement
- GSM Module SIM800L
- rechargeable battery pack.
- Buzzer/Alarm
- R 307 fingerprint module
- Switches
- Bread board
- LEDs
---
### References:
- GPS-based vehicle tracking and theft detection systems using Google Cloud IoT core f irebase PV Crisgar, PR Wijaya, MDF Pakpahan... (2021) 
- GPSandGSMbasedanti-theft vehicle system M Shaikh, M Shah, KE Momin (2018) 
- Smartsecurity system for vehicles using internet of things (IOT) M Sathiyanarayanan, S Mahendra (2018) 
- https://www.dcceew.gov.au/environment/protection/ozone/ozone science/antarctic-ozone-hole: :text=The

---
