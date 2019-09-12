# Automated-Latch-using-a-Secret-door-knock
This was our project for Technovation'19 conducted by ISA-VESIT.
We won 1st Prize.

We have created a Automated Latch which can be opened using a secret door knock.
Also This knock mechanism can be ON by an Android App.
Latch can be close in Android App.
We have 3D printed Latch components which includes a Latch and a Linear Actuator.

We have refered this instructables post and made some changes in it.

https://www.instructables.com/id/Secret-Knock-Detecting-Door-Lock/

Components:

->NodeMCU ESP8266

->Servo Motor

->Pizeo Buzzer

->Arduino UNO (Power supply for Servo motor)

->1 Push button

->1 Red LED

->1 Green LED

->1 1M ohm resistor (1/4 watt)

->2 560 ohm resistor

We have used a servo motor instead of gear reduction motor.
NodeMCU can provide only 3.3V output. So, i.e. we used a Arduino UNO to power it.
Circuit design is almost same as reference post.

App is created on Thunkable Platform. .aia file is included.
After connecting a NodeMCU to WiFI, note it's IP address from WIFI router setting or using a 'Fing' App.
Then update this IP in Thunkable. Change Home URL of Web-Viewer1 in 'Web' Window.

Project Members:

Raghav Potdar

Rahul Sohandani

Prathamesh Pendal

Harsh Kotwal
