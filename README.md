# DIY-Label-Printing-Machine

![image](https://user-images.githubusercontent.com/19898602/185733916-70120dc5-efc2-424a-809e-5a1b4a5e91db.png)


Hello friends 
In this post I made a CNC machine which draw text on Masking tape in this way we can create cool labels to stick.
We can create cool labels for our workshop, office or home.

Here I have created G-code of text in android phone itself using text to CNC android app.
And I have used GRBL controller android app to send G code to machine 
Laptop is not at all needed to print label in this way is handy, compact & portable. You can print label anywhere any time just need to provide 12V DC power.
I need to replace all Z1 command to M3 S255 and Z0 to M5 in G-code in text editor in order to run servo up and down.

# COMPONENT REQUIRED

1. Arduino Nano
2. [Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy)
3. Micro Servo motor
4. A4988 Stepper driver
5. Nema 17 Stepper motors
6. Timing pulley
7. Timing belt
8. Linear rails
9. 3D printed parts 
10. Some hardware


![image](https://user-images.githubusercontent.com/19898602/185774503-977b8654-0069-41df-bad8-9707fc8d942e.png)
![image](https://user-images.githubusercontent.com/19898602/185774511-fcaf497a-b15d-4df1-a0d7-1e09d0545691.png)

First I made base of the machine from the 12mm wooden block.

I have used birch ply to make base foundation of machine.

Then I 3D printed a yellow part which help to clamp stepper motors onto it.

Two stepper motors have to be mount on this 3D printed parts facing in opposite direction.


![image](https://user-images.githubusercontent.com/19898602/185774559-f6516677-65a0-408b-af51-4901388a3a1d.png)
![image](https://user-images.githubusercontent.com/19898602/185774640-380a5637-dd06-4146-b4d3-d58d702df963.png)


Then I used my home CNC router to cut the 6mm acrylic sheet, This sheet will became base of X axis of our machine.
We’ll latter mount X axis onto this 

Whenever you try to machine Acrylic sheet be sure that acrylic must be cast acrylic not extruded acrylic.

![image](https://user-images.githubusercontent.com/19898602/185774649-57a633cb-564e-4c1b-b697-f7f729776f22.png)

Then I used 9mm Linear rails to make X axis of the machine.

This linear rails are very much precise and heavy duty 

I used 2 8mm pillow bearing to hold the T8 lead screw. 

One end of lead screw is connected with timing pulley and this 8mm lead screw is then connected with shaft of stepper motor.

So that when stepper motor rotates then 8mm Lead screw will rotate through timing belt. And move linear rail forward and reverse.


![image](https://user-images.githubusercontent.com/19898602/185774727-fa4f615e-f16f-4610-905e-51005b7441e3.png)


After that I have design a pen holder for X-axis this 3D printed part will mount on X axis mutually connected with the 

8mm lead Screw.

Then after I placed 2 3mm smooth rod for up and down moment of pen.

For up and down movement of pen I have used on Micro servo motor. This types of stepper motors are very small in size and have enough power 

For such works.



![image](https://user-images.githubusercontent.com/19898602/185774837-84a72ca6-bfcd-41d5-993b-943b6a43d611.png)
![image](https://user-images.githubusercontent.com/19898602/185774853-cc9ffe7f-6cf1-4b83-9495-56a57e635991.png)


I have used my [Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy) in this project.

If you don't know about my multipurpose PCB then definitely check out my [Multipurpose custom PCB](https://oshwlab.com/sharmaz747/multipurpose-pcb_copy_copy_copy)

this PCB can be used for many jobs It can able to connect 11 components at a time to the PCB. 

We can run 

2nos stepper motor

2nos DC motors

2nos Servo motor

at a time 

and After designing PCB in my favourite PCB editor tools. Now it’s time to order PCB

I trust on [JLCPCB](https://jlcpcb.com/IAT ) for ordering PCB they have very fast shipping service and low rates for quality PCB.

If you are new customer for JLCPCB You will also get welcome coupons from [JLCPCB](https://jlcpcb.com/IAT ) so hurry up & visit [JLCPCB](https://jlcpcb.com/IAT )


![image](https://user-images.githubusercontent.com/19898602/185774980-a90d76c3-e7c0-4ebc-8b69-779d435e431b.png)

Wiring is very very simple and neat and clear thanks to the PCB.

Just plug the Stepper motor wires, servo motor wires and power supply to PCB

That's it our wiring is complete. 

![image](https://user-images.githubusercontent.com/19898602/185775032-172ed960-53a4-446b-9687-df4d6cf92e94.png)

![image](https://user-images.githubusercontent.com/19898602/185775038-c3277058-79d4-4956-8d36-6021c8b56aa4.png)


We are printing Label on paper tape so we need something to hold the paper tape. so I printed this part to hold the paper tape.


I design it in such way that it continue to maintain pressure on paper tape from inside due to its design. 

So it will be sure that paper tape not get loose while in operation. 

![image](https://user-images.githubusercontent.com/19898602/185775126-183d75f8-25b1-477d-8a5b-58458d47d97e.png)

So now we finally placing the paper tape onto the shaft of stepper motor 

Paper tape must be in aligned with the tip of pen above it.

in this way out construction of paper tape label printing machine is completed.

![image](https://user-images.githubusercontent.com/19898602/185775185-65de3e14-7d69-4f0e-b1dd-08e811ec6b63.png)
![image](https://user-images.githubusercontent.com/19898602/185775194-cf7108c8-7b5c-444a-8e6b-1b8d6e39ff09.png)

Here I totally control label printing machine from the mobile 

I used this mobile app to generate G-code of text 

https://play.google.com/store/apps/details?id=com.microtechstelladata.texttocnc&hl=en_IN&gl=US


I used this mobile app to send G-code to label printing machine

https://play.google.com/store/apps/details?id=in.co.gorest.grblcontroller&hl=en_IN&gl=US


![MVI_0001_8](https://user-images.githubusercontent.com/19898602/185775287-492abc69-5a35-4389-a524-83e72f01c600.gif)








