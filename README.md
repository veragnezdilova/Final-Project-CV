# Final-Project-CV
## Final project for exam on 27.03.2024

_Link for the presentation: https://docs.google.com/presentation/d/1-nTX48RiYHosMvMh7J4QUaPt6F2F3QpGeRed5-xz-rY/edit?usp=sharing_

The purpose of the project was to track the movement of vehicles in a traffic surveillance and detect colors of cars.


 
The main loop iterates over each frame of the video:

● Each frame is converted to grayscale for car detection

● Car detection is performed using the detectMultiScale method of the Haar Cascade classifier

● Rectangles are drawn around detected cars

● Dominant color within each detected car region is determined using K-means clustering

● Text displaying the closest color name to the dominant color is added to the frame

