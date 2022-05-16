# Ubor
Hi
Welcome to Ubor


Updated: May 2022

# Introduction
Ubor is a lightweight mock of Uber and was completed as a team for our Software Architecture class(SENG401) at the University of Calgary. 
The goal of this project is to learn more about mobile development, AWS and its different microservices. Ubor has the main functionalities 
such as drivers and users accepting a ride, distance/time calculation and real time location updates. The front end was built using React-Native and tested within Android Studio.
The back end is connected to AWS using AWS Amplify. Through Amplify we are able to easily connect it to other AWS Microservices. We used AWS Cognito for login authentication, AppSync
for GraphQL and DynamoDB for storage. We also used Google Maps API to get real time location updates. 

# Video Demonstration
The 90 second video below demonstrates the main functionalities of Ubor such as login(AWS Cognito), location search, distance calculation and finally accepting a ride.

https://user-images.githubusercontent.com/77874716/168509944-390fcb06-4a8d-479c-b2b2-c8e1b8b835d4.mp4

# Installation
1. Must install android studio. The virtual device chosen is Pixel4

# Running the program
Steps to compile and run this application, the program can be run from two options.
1. Clone The Repository on your local device.
2. Starting from the driver's side, cd DriverApp folder
3. perform npm install if it is the first time running, then npm start. React native will now start


# Sample Screenshots

## Driver App: 
![image](https://user-images.githubusercontent.com/77874716/168176866-7609efff-24a5-4e15-86ca-edcb745a5bbd.png)