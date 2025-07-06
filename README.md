# Home-Automation
I have created an online simulation on workwi, where home automation is controlled by Blynk application.
<br>
The Home automation is nothing but Automating our home elctronics appliacations such as Television, Fridge, lights, etc. with some sort of control. 
<br>
<br>
Components used :
<br>
1.ESP25
<br>
2.Breadboard
<br>
3.LEDs (4)
<br>
4.Switches (4)
<br>
5.Relays (4)
<br>
6.Vcc
<br>
7.Gnd
<br>
<br>
STEPS PERFORMED FOR CREATING THE CIRCUIT:
<br>
Step 1: Connected the circuit with esp25 :
<br>
Relay 1 - ESP 13 pin
<br>
Relay 2 - ESP 12 pin
<br>
Relay 3 - ESP 14 pin
<br>
Relay 4 - ESP 27 pin
<br>
Relay Vcc - +ve of breadboard
<br>
Relay Gnd - -ve of breadboard
<br>
Switch 1, 2,3,4 - Gnd 
<br>
Switch 1 2.1  - ESP 26
<br>
switch 2 2.1 - ESP 25
<br>
Switch 3 2.1 - ESP 33
<br>
Switch 4 2.1 - ESP 32
<br>
<br>
Step 2 : Created a Template with switches connected to it
<br>
Firstly i went to my Template and created Switches titled as Relay 1, Relay 2, Relay 3, Relay 4 and connected them with v1,v2,v3,v4. and saved the design.
<br>
<br>
Step 3 :  Authentication code is taken from the blynk application and imported in the code.
<br>
<br>
After saving the design, there will be an Authenticated code where we can see the Template ID, teamplate name etc. where we need to import in the code.
<br>
<br>
Step 4 : Imported Libraries like BlynkESP32_BT_WT.
<br>
<br>
Step 5 : Wrote the code in WorkWi application with imported libraries.
