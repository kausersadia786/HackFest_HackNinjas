# HackFest_HackNinjas
This is the hack source code created by team Hack Manias in HackFest-2020, annual Hackathon in IIT(ISM)-Dhanbad.

We created a Hand Gesture controlled automatic room prototype using Computer vision and Raspberry Pi for Hardware-Software interaction.

We used OpenCV as our library of python distribution for Computer Vision, i.e. Hand-Gesture Recognition.

Raspberry Pi 2-B was used to run our python scripts and interact with hardware as detected by the Gesture detection.

Pre-requisites :-

Python2.x.y >= Python2.7.0 / Python3.5.x >= Python3.5.1 / Python3.6.x >= Python 3.6.2 (However our some codes may vary from python to python but only the print statement syntax is different, other libraries are common.)
OpenCV(python-distribution), we used 2.7.4 in Raspberry and 3.4.2 in our systems.
Raspberry Pi, atleast 2-B. Even 2-b was too slow for such heavy tasks, so we had to optimize our codes seriously.
We used background deletion by pixel differentiation and contours formation to recognise the gestures.

Raspberry GPIO pins were used to control hardware which can be extended to AC circuits too using relays.

Please refer to the image for raspberry pi connections.

Happy Coding!

Sadia Kauser
