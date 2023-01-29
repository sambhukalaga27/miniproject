# miniproject
Hand gesture detection system that will control the slides without interfering with the presentation can be quite useful. We chose to make it possible for users to control the slideshow with hand gesture.

ABSTRACT
The presentation serves as a medium of interaction between the speaker and the listener. Using a mouse, keyboard, or remote control to advance or rewind the slides is possible, but these Human-Computer Interactions (HCI) tools are cumbersome and uncomfortable. However, a hand gesture detection system that will control the slides without interfering with the presentation can be quite useful.We chose to make it possible for users to control the slideshow with hand gestures

Keywords:  Hand gesture recognition, Gesture control, HCI

MOTIVATION
We need digital technology to perform daily tasks like working, buying and communicating because of its increased interconnection. A gesture is a form of nonverbal or non-vocal communication that uses movement of the body to convey a particular message. Hand gestures serve the purpose of communicating information when engaging with other individuals.

PROPOSED SYSTEM
The proposed system controls the slide-show presentation solely through static hand gestures. These static hand movements are segmented before being analysed further. The image can be used to extract the Histogram-of-gradient feature after segmentation and processing. After HOG feature extraction, the extracted features are compared using k-nearest neighbour classification to the features of the gesture image held in the database. 

ARCHITECTURE
This project makes use of the libraries- MediaPipe, OpenCV, and NumPy, which must be loaded. The primary camera provides the video inputs. Now that MediaPipe is being used to identify the video as input from the camera, the mphand.hands package is being used to identify the gesture. Next, we used a pointer to access the presentation. The input processing must then be completed by converting the input image to an RGB image. Then it's your turn to specify the thumb and finger points. NumPy is used to modify the required output of this operation. In this process, presentation is managed by the hand range. The NumPy library for the Python programming language is necessary for computing. 

CONCLUSION
The program used in this research makes use of hand gestures to control software in a straightforward and useful way. Since it doesn't require very high-quality cameras to detect or record hand movements, a gesture-based presentation interface can be utilized in real life on basic PCs with inexpensive cameras. The technique records the locations of the index finger and counter tips on each hand. The main objective of this kind of system is to effectively automate system components to make them simple to control. As a result, we used this strategy to make the system run smoother with the help of this program in an attempt to make it more realistic.
