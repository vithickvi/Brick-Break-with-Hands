# Brick-Break-with-Hands
Brick Break Game played with our real hands using Webcam and OpenCV

##
Hand Gesture Recognition a highly anticipated technology of this century, has different face towards our environment. We developed gesture interface device which eliminates the use mouse and the keyboard from our traditional computers. In this system a webcam is used to track the objects and a computer vision algorithm is used to control the devices based on the webcam input. It can be stretched to any of our daily applications, such as Television, Gaming...Etc 
The traditional user interfaces relies on the use of mouse and keyboard. But it is difficult to use these devices continuously. The aim is to develop a gesture based interface, where the system uses inbuilt webcam to track the hand movement and controls the mouse pointer accordingly. 
The first step towards this is the development of object tracking mechanism. Though there several object tracking algorithms are readily available, CAMSHIFT algorithm provides more accuracy when compared to MEAN SHIFT and others. The other option is the use of HAAR classifiers but involves a tedious process of training and also we cannot extend it to different objects.  
The modified OpenCv CAMSHIFT algorithm to track our objects. The Second Step is to distinguish the object color from our skin color, so we added a red ribbon to the hands such it not only provides a clear view but also gives an option for different gestures. Finally the algorithm tracks the hand using the input from the webcam and the co-ordinates are extracted 
from the tracked object for every frame and passed to windows m functions. Thus whenever the object is moved via webcam, the cursor also moves accordingly. Different gestures are used to produce click functions and other operations.  
Extending it to the famous gaming application Brick Break in python with the help of pygame made the game more interactive and interesting 
