## Swing tracker using OpenCV in Python
### OpenCV
OpenCV is the huge open-source library for computer vision, machine learning, and image processing and now it plays a major role in real-time operation which is very important in today's systems. By using it, one can process images and videos to identify objects, faces, or even the handwriting of a human. OpenCV has a bunch of pre-trained classifiers that can be used to identify objects such as trees, number plates, faces, eyes, etc. We can use any of these classifiers to detect the object as per our need.

### Motivation
I breathe cricket. As a cricket fanatic, I always try to connect my passion with technical skills. Though I couldn't get a chance to enjoy the game on the field I try to do things which is cricket related. Now a days in any cricket match more or less every decision taken by the umpires are rechecked by the third umpire. Whether it's a catch or LBW or even a noball third umpire checks with the technology (Hotspot/snickometer) available in hands and comes to the conclusion. Hence, I tried usng OpenCV library to spot the ball and try to track the movement of the ball throughout the journey from the bowler's hand to the wicketkeepers glove. 

### Data
I used a video of Jimmy Anderson's swing bowling with pink ball from <a href="https://www.youtube.com/watch?v=XRviyt1lioA">YouTube</a>. It was a D/N test match from the ashes 2017.
### Framework & Packages
To start the project first of all you have to clone the repository and the install all the packages from requirements.txt
```
 pip install -r requirements.txt 
```
### Run the system
Open your anaconda prompt go to the main folder
```
python swing_tracker.py --video swing2.mp4
```
the command includes the python file as well as the video file. The code is applicable for the live webcam also.


### Fututre Scope
    This project is just a first step of implementing the hotspot.

<a href="https://youtu.be/SlPtlaAIG24">Check the Demo</a>