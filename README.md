# AutoNavigator
Self-Driving Car Prototype through Machine Learning

Autonavigator is about demonstrating the self-learning capability and embedding intelligence in a Remote controlled (RC) car to exhibit a prototype of self-driving car using combination of advanced techniques like Machine Learning with microcontrollers, android and networking technologies. 
The working system demonstrates that our model gives significance result training accuracy and cross validation accuracy of about 96.3% and 93.1% respectively.

- About Auto-Navigator -

1. Self-driving car prototype through Machine Learning (Feb 2018)
2. Technologies- Machine Learning, IOT, Image processing

- The system comprises of following components –
1. Remote control(RC) car and image capturing device
2. Server
3. Microcontroller

The basic functioning of the system is as follows –

The remote controlled car is used for autonomous navigation along any path on which it’s placed to navigate. A
smartphone camera holder that is used to hold the image capturing device, e.g. smartphone, is placed on the top
of the RC car. The function of the image capturing device is to send the images of the path on which the car
navigates to the server. The image capturing device uses android application e.g. Netcam/SmartCam to send the images
to the server using REST API.

The design of the working of the system can be divided into two phases –
a) Dataset generation (self-generated dataset) and training of machine learning model(Refer Training_imgs folder)
b) Real time testing and navigation of the RC car

- Dependencies

1. Tensorflow - pip install tensorflow
2. Keras - pip install keras
3. sklearn - pip install scikit-learn
4. OpenCV - pip install opencv-python
5. Arduino IDE - https://www.arduino.cc/en/Main/Software
6. Other Hardware Requirements - Remote Controller Car, Remote Controller, Smartphone Holder, Electronic Circuitry(PCB, Arduino Board, Optocouplers, Connecting wires and Cables)
7. Other Dependencies exist, but they will be resolved during the pip install of the above.

- Training the model -

The model can be trained as mentioned above. Sample training images have been provided in the Training_imgs folder.
- Test the Application

Perform the hardware and other setup as mentioned. Run the application through drive_.py file, the real-time capturing of images from the smartphone will provide testing images to the trained machine learning model.
The model will predict the navigation decision, the car navigates.
