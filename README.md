# Deep-Learning-Project
Project about deep learning and computer vision for self-driving cars and fleet management
This project uses computer vision to learn the pattern of cars at parking lots and other facilitites. The model will optimize and make the best use of time and energy in the most efficient manner.

Currently takes a picture(first frame of the video feed) of the parking lot and using Mask-RCNN, notices the cars in the space. Since I haven't trained it well enough to identify parking lines, it's scalability is very low.
After identifying the cars in the picture, it analyzes each frame from the video feed and checks if the car is still there. If not, it sends an alert to the user. That is where it identifies a free spot. 
As it is now, it is not scalable and my team will be trying to get it to localize per the location of the user (GPS) and use Google Maps (Satellite view) to aid in identifying the lanes. 
The problem is tougher than I imagined and we have a long way to go. 
Influenced by Adam Geitgey
