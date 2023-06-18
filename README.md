# Fire-Fighting-Rescuers-Eye-bot
The main objective of our project is to design and build a
robot that can perform two different tasks: controlling the fire
and finding the injured person in a disaster scenario. The robot
has two modes of operation that correspond to these tasks.
A. Fire Fighting Mode
This mode is activated when the robot detects a fire in its
vicinity. The robot uses an ultrasonic sensor to measure the
distance to the nearest obstacle and avoid colliding with it. The
robot also uses an IR flame sensor to determine the direction
and intensity of the fire. The robot navigates towards the area
where the distance to the obstacle is the maximum, and stops
when it reaches the fire zone. Then, it turns the water pump
on but the source to the water body is connected to different
place to make a safety use of our sensor used module.Then,that
source completely put out the fire. The robot also has an ESP
32 cam module that captures video data and sends it to a
device, where a machine learning algorithm processes the data
and detects the fire regions in the images.
B. Monitoring Mode
This mode is activated when the robot needs to find the injured people in the disaster area. We use a Bluetooth
module (HC 06) to communicate with the robot and control its
movement through our input. The robot also uses the ESP 32
cam module to take pictures of its surroundings and compare
them with a database of human faces. If the robot finds a
match, it means that it has found a person. The robot then
takes a photo of the person and uploads it to Google Drive,
where users can access it and provide assistance. If the robot
does not find a match, it means that there is no person in that
area. The robot then continues to move forward and search
for other people.
