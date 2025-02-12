# Hand Gesture Recognition 

The inspiration of this project was actually from my favourite hero Iron Man.This was is in Iron Man 3 where he calls his suit with Hand Sign and  that is what gave me the IDEA!!!.

![VjMwAT](https://user-images.githubusercontent.com/73626462/161976138-6e667337-c4b0-4934-9a7e-b36c71cca5c7.gif)

Coming Back to the Project 

## Index
1. [Introduction](#Introduction)
2. [Workflow](#Workflow)
3. [Data](#Data)
4. [Network on which the data will be trained](#Network-on-which-the-data-will-be-trained)
5. [Real Time Testing](#Real-Time-Testing)

## 1 Introduction
Today in the world of evolving technology everything is becoming from real to virtual.All the people who we had to meet to talk to, we can talk to them via Skype or do a phone call.These advancements have bought the world closer and made it easier for us to live.Like that only to advance further is the goal of this topic.
Gestures have been used from the pre-historic period right from the stone age and  it is the basic form of human interaction without words,However nowadays we interact more with machines rather than people so, therefore, to make our interactions easy with the machine is the goal of this project.These gestures should be able to communicate with all kinds of machines right from radio to computer and going further ahead with Augmented reality and Virtual reality.The gestures are a very important application in virtual reality like Metaverse because objects like the mouse, keyboard, and joystick become inefficient and cumbersome.Thus giving rise to a new kind of human-computer interaction.In this project, I will use MediaPipe and OpenCV to record the gestures and create the data.The gesture would be recorded for 30 frames only.
After recording the gestures, I will train the gesture by using LSTM.After training the model on the network with the highest accuracy seeing the results in real world application  

## 2 Workflow
![image](https://user-images.githubusercontent.com/73626462/161989537-3a81f963-d871-4849-892b-e2abfc10d03b.png)

## 3 Data
Here the Data has not been taken from any online source but it has been generated by me only.I have generated the Data by using OpenCV and MediaPipe.The Data has been generated for 10 actions Take-off, Up, Down, Left, Right, Forward, Back, Turn Left, Turn Right.30 frames of each action have been recorded and from those actions, the right-hand coordinates have been noted down with the help of MediaPipe.

![ezgif com-gif-maker](https://user-images.githubusercontent.com/73626462/161993915-5773a372-695a-444a-908b-a2a885568fa7.gif)

The gestures are 

![image](https://user-images.githubusercontent.com/73626462/163742931-2d8c2005-0a73-439b-9be4-c468ee4e5c4a.png)

These gestures are stored in their respective folders


![image](https://user-images.githubusercontent.com/73626462/161999953-e53f96b4-2907-4719-b5dd-5c214900d45a.png)



## 4 Network on which the data will be trained
Here I have created my own network. For gesture recognition In the Network, I have used LSTM layers.The reason I have used LSTM layers is that it has long-term dependencies as it does not forget the things learned from the previous data.This is the network which I have made to train the data on.

![image](https://user-images.githubusercontent.com/73626462/162001439-bb0936f2-eb99-462a-832d-4473970f1acf.png)

## Accuracy of the model 
Here we can see the accuracy of the model

![image](https://user-images.githubusercontent.com/73626462/162001574-4cc9144d-eb76-4090-9e40-0b53861a77cf.png)

## 5 Real time testing
For the Live Demonstration I have used the DJI Tello Drone.This Drone is used for Drone educational purposes and is easy to program.The DJI Tello drone has its own python package which makes it easy to control the drone and doesn’t require to code a lot.The demo of this Project Has been recorded Since the drone has to be connected to the computer via Wi-Fi.

![image](https://user-images.githubusercontent.com/73626462/162005490-6f4a661f-96d6-4a59-8195-86687f43d521.png)

Here is the Drone

https://user-images.githubusercontent.com/73626462/162007233-e6e569a7-9148-497d-b6c5-9e826b8ef7ca.mp4

And this the live working of the Drone. However just like Mark 42 the drone is a bit difficult to control 😂😂😂😂 .As there is a lag between the laptop and the drone.








