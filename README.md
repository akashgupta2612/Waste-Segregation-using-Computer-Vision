A waster segregation bot that segregate waste into biodegradable and non-biodegradable using different components:
1. Hardware: Arduino(a microcontroller), Servo Motor, Webcam, etc.
2. Convolutional Neural Network(CNN) in Python using Keras and TensorFlow.
Working:
Firstly the image of waste is feed into the trained CNN from the webcam then the CNN classifies the waste as Biodegradable(1) or Non-Biodegradable(0) and pass the output to the Arduino through the connected port.
Then the Arduino passes the respective instructions to Servo Motor which rotates in clockwise or anti clockwise direction to put the waste in the desire container(one for biodegradable and one for non-biodegradable).
