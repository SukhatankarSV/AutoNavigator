# AutoNavigator
- Self-Driving Car Prototype through Machine Learning

This project is about demonstrating the self-learning capability and embedding intelligence in a Remote controlled (RC) car to exhibit a prototype of self-driving car using combination of advanced techniques like Machine Learning with microcontrollers, android and networking technologies. The working system demonstrates that our model gives significance result training accuracy and cross validation accuracy of about 96.3% and 93.1% respectively.

- About Auto-Navigator -

1. Self-driving car prototype through Machine Learning
2. Technologies- Machine Learning, IOT, Image processing

- The system comprises of following components – 
1.	Remote control(RC) car and image capturing device
2.	Server 
3.	Microcontroller 

The basic functioning of the system is as follows – 

The remote controlled car is used for autonomous navigation along any path on which it’s placed to navigate. A smartphone camera holder that is used to hold the image capturing device, e.g. smartphone, is placed on the top of the RC car. The function of the image capturing device is to send the images of the path on which the car navigates to the server. The image capturing device uses android application e.g. Netcam to send the images to the server using REST API.

The design of the working of the system can be divided into two phases – 
a)	Dataset generation (self-generated dataset) and training of machine learning model(Refer Training_imgs folder)
b)	Real time testing and navigation of the RC car

- Dependencies - 

1. Tensorflow - pip install tensorflow
2. Keras - pip install keras
3. Numpy - pip install numpy
4. sklearn - pip install scikit-learn
3. Arduino IDE - https://www.arduino.cc/en/Main/Software
4. Other Hardware Setup - Remote Controller Car, Remote Control, Smartphone holder, Electronic Circuitry(PCB, Optocoupler, Wires, Arduino Board and Cables)
5. Other Applications - SmartCam
6. Other Dependencies exist, but they will be resolved during the pip install of the above.

- Test the Application

To run the application, perform the hardware setup and connection to laptop as mentioned above. Run drive_.py to run the model. Real-time capture from the smartphone camera provides testing images to the RC car. The model predicts the navigation decisions and the car navigates.

