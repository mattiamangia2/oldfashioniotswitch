# oldfashioniotswitch
Old Fashion IoT switch, for interacting with a phisical switch for turning on and off electrical boiler, in order to save up Electricity for hot water. Then making it possible to activate it via Google Home or Alexa

Modern smarthome hardwares are cool, but old-fashioned solutions still kill it.
Yes, there are ready-made solutions available on the market for smart homes, that allow people to automate switches in an easy and aesthetical way, such as Sonoff and Shelly (to mention the main firms). 
 
But, here comes the fun: 
I wanted to practice and use arduino nano 33 IoT and a 3d printer and I couldn't wait to make them work together in a fun project. 
And the best way to do that, was to combine some of my skills to create an educational project that contains 4 major challenges: 
 
1) Conceptualizing and drafting the solution with all boundary conditions; 
 
2) Write the code in C++ and discover the beautiful world of Arduino hardware and software; 
 
3) Design, dimensioning and prototyping of the shell and the mechanism that pushes the button, and relative slicing and 3d printing; 
 
4) Adapt a solution that is not natively made for using servo motors, rather adapting a dimmerable light sketch to allow Google home to move the servo motor of the solution. 
 
Result: something cool and fun. 
Will I really use it in real life? No, we've already installed a Sonoff to automate the heating system, but still, it's something cool and worthy of being published. 
 
Objecive of this project, is creating a Mechanical element, that can interact with a switch. The switch, is connected to an electrical boiler that is used to heat the water used for taking shower. The idea starts from the need of saving up energy for hot water, while making it possible to have hot water ready on request. Then, I decided to make it possible to let Google Home or Alexa communicate with it. To do so, I had to use a workaround in setting up the thing on Arduino IOT, cause there is no ready-made solution to connect a Servo Motor. The closest device possible that "thinks" in percentage or degrees was a dimmerable light. That's why I decided to set the code as I was talking to a dimmerable light, then converting percentage to rotational degrees. 



Components: 
Arduino nano 33 IoT;
Servo Motor SM-S2309S;
Anycubic Kobra 2 Pro 3d Printer with PLA filament


Video here:
$ https://vm.tiktok.com/ZNeccmdwG/ $ 
