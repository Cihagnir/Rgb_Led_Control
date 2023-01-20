Hello There .... 

-----------20/January/2023 ------------ 
In this project, I aim to control my led with the computer. However, I need to figure out the ESP32 and TCP 
communication first. 

Because of that, I decided to start with Stm, and then create a bigger project on that basis. That should 
be funnier than just waiting and learning progress. Let's talk about what I did and couldn't do.

We have one stript LED led which is powered by 12V.  It was basically controlled with the remote controller 
like a tv. That sh*t is not good-looking and not cool too. Thus I decided to do that with Stm to understand how 
can I control my stript led properly. After handling the circuit and control stuff I will upgrade my 
stm with ESP and create a TCP server.  

In the circuit, we have 3 N-channel Mosfet which controls the ground connection of each color stript of the LED.
 We apply PWM signal the each of the MOSFETs. With that, we can control the voltage above the led strip that 
creates the color difference I guess. 

I keep updating that file with the commits and date mark. So that makes evey thing easy to understand for you.

kachovvvvv 