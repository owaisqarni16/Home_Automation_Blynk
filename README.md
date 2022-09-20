# Home_Automation_Blynk

Project Description

This Project can be used to control your house lights, fans or can add some automation functionalities, for that you can use ESP8266 and Blynk app which is easy to use and hence can be easily installed by anyone as DIY project.
Arduino Programming language is used here to program our micro controller(ESP8266).

BLYNK APP

To configure BLYNK go to their official website.
  https://blynk.io/
Blynk was designed for the Internet of Things. It can control hardware remotely, it can display sensor data, it can store data, virtualise it and do many other cool things.
There are three major components in the platform:
•	Blynk App - allows to you create amazing interfaces for your projects using various widgets we provide.
•	Blynk Server - responsible for all the communications between the smartphone and hardware. You can use our Blynk Cloud or run your private Blynk server locally. It’s open-source, could easily handle thousands of devices and can even be launched on a Raspberry Pi.
•	Blynk Libraries - for all the popular hardware platforms - enable communication with the server and process all the incoming and outcoming commands.
Now imagine: every time you press a Button in the Blynk app, the message travels to  the Blynk Cloud, where it magically finds its way to your hardware. It works the same in the opposite direction and everything happens in a blynk of an eye.


Installing the Blynk App on the Smartphone
•	Open the Play Store and install the Blynk App.


 ![image](https://user-images.githubusercontent.com/101192246/191269032-fb5c7fa5-6eae-4dab-9177-4f347f3c6bbf.png)



Blynk App
•	Once the app is installed either login to it using Facebook or create a new account on Blynk and log in using that.
•	After logging in, create a new project by clicking ‘New Project’.



![image](https://user-images.githubusercontent.com/101192246/191269538-4f61fdc0-eb86-4fbb-a19c-6a2ec0fb8802.png)

 
 
New Project
•	Give the project a name of your liking, in my case, it’s “My Room”. Select the hardware device as NodeMCU and select the connection type as WIFI, and hit create.



 ![image](https://user-images.githubusercontent.com/101192246/191270940-86c47184-7c43-4eef-bd91-0dafeeee9a34.png)



New Project
•	Now Blynk will send an Auth token to your email id. We will use this “Auth token” . We will add that auth token in our source in auth variable.
•	Now since we are using a four-channel relay, I’ll add 4 buttons on the blank project. To add a new button just click anywhere on the blank area and select button from the side menu that pops up. You can place the button anywhere on the screen.



 ![image](https://user-images.githubusercontent.com/101192246/191269787-b60e6932-cdbd-40b3-9a62-0f322dd2a47b.png)



New Button
	Click on the “Button ” and in the textbox select the pin as digital pin V13. Below the textbox, give it an “ON/OFF Labels”. I’ll name it “Light 1” as I’ll use it to control light. To know about the Virtual Pin, Check this.
  
  
  ![image](https://user-images.githubusercontent.com/101192246/191269928-e75db9be-2cc2-45ad-b0aa-b5732126bb92.png)

