# Ubor

Updated: May 2022

# Introduction
Ubor is a lightweight mock of Uber and was completed as a team for our Software Architecture class(SENG401) at the University of Calgary. 
The goal of this project is to learn more about mobile development, AWS and its different microservices. Ubor has the main functionalities 
such as drivers and users accepting a ride, distance/time calculation and real time location updates. 

The front end was built using React-Native and tested within Android Studio.
The back end is connected to AWS using AWS Amplify. Through Amplify we are able to easily connect it to other AWS microservices. We used AWS Cognito for login authentication, AppSync
for GraphQL and DynamoDB for storage. We also used Google Maps API to get real time location updates. 

# Video Demonstration
The 90 second video below demonstrates the main functionalities of Ubor such as login(AWS Cognito), location search, distance calculation and finally accepting a ride.

https://user-images.githubusercontent.com/77874716/168509944-390fcb06-4a8d-479c-b2b2-c8e1b8b835d4.mp4

# Installation
1. Download Android Studio and Node.js to properly run the application. Android Studio provides the tools to emulate Android devices and Node.js is used to run the application.

2. In the Device Manager on Android Studio, download a new Android phone emulator. In our case we chose Pixel4 as our virtual device. Run the emulator using the play button on the Device Manager window.

3. Open two command prompts. On each command prompt, navigate to the Ubor folder. The user can then pick whether they would like to run the User application or the Driver application.

4. Upon choosing the application that the user would like to run, navigate to the inside of the respective folder on both command prompts (ie. if you picked the User app, then navigate to the User app on both command prompts).

5. First, run the command “npm i”. Then, on one terminal, run the command “npm start” and on the other terminal, run the command “npm run android” (Windows). When using Mac if you encounter any issues type “chmod 755 android/gradlew” and into terminal then type “npx npm start” and open another terminal and type “npx npm run android”. If you are having troubles with both Windows or Mac you can enter the command “npm i” again.  

6. After configuring, building, and then downloading the application onto the emulator, the emulator should then run and the application can be tested. 

# Sample Screenshots

## Driver App: 
![image](https://user-images.githubusercontent.com/77874716/168176866-7609efff-24a5-4e15-86ca-edcb745a5bbd.png)