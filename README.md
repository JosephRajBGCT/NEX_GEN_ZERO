This Project is done by a group of 4 members of Government college of Technology Coimbatore in their Third year of BE ECE course.The project was presented on 8th Feb 2024.


The project is used to solve the major issue faced by India on 2nd June 2023 when Three trains had collided with each other en route.

Vibration sensors are used to check if there is a continuous streak of vibration for more than the threshold time and if there is such a vibration, then it signifies that a train has crossed the sensor and the similar setup is done in other end of the Track.

When both the sensors detect trains in the same track then using LoRa communication protocol (Not used in project) both the trains are alerted and the emergency brakes are automatically applied on both the trains.

Here the "Vibration_Sensing.ino" file is the Arduino code for detction of the train and rotation of the servo motor which represents the Train braking system.

The one additional feature that this New train system accomodates is meant for the safety of ignorant citizens or suicidal people who accidentally/incidentally end up on train tracks when train nears them. This feature uses a camera module fit in the front of the train to continuously check for any anomalies in the train track and if it detects any person or any small animals, the Blowers (Here represented by a motor) on the train are activated and the person is pushed out of the track.According to the animal detected, the blower's RMP is decided.

The file named "object_detction.py" is used to detect the animals using on-board camera and send appropriate bits to the COM4 port while the "motor_response.ino" is responsible for adjusting th RPM of the Blower according to the bits recieved.

Authors:
Joseph Raj B
Srishivanth R F
Krishna Prasath S
Vignesh K
