# Rani's TDF Repository

# Outline
[week 1](README.md#Progress-Report-1)

[week 2](README.md#Progress-Report-2)

[week 3](README.md#Progress-Report-3)

[week 4](README.md#Progress-Report-4)

[week 5](README.md#Progress-Report-5)

[week 6](README.md#Progress-Report-6)

[week 7](README.md#Progress-Report-7)

[week 8](README.md#Progress-Report-8)

[week 9](README.md#Progress-Report-9)

[week 10](README.md#Progress-Report-10)

[week 11](README.md#Progress-Report-11)

---
# Progress Report 1 #

## Reflections ##
This week, I designed and did some research on Rhino, set up my github, explored the wiki page, and laser cut a bookmark. Firstly, although I have had experience with github, I found that I had forgotten a lot of aspects of how to use a github repository. To help, I watched a few videos to refamiliarize myself and asked classmates clarifying questions on what file they were editing and how they were doing so. 

I also took some time to do research on laser cutting and 3D printing. I completed the required videos and quizzes and working with a design specialist to ensure that I knew the intricacies of laser cutting. I first started by cutting a simple square into plywood, and then egraving a line across the square to practice that technique. This set me up well for the small laser cutting assignment we needed to complete. 

For the laser cutting assignment, I made a small bookmark. Something I learned is to increase the raster percentage in the laser cutting settings, to improve the quality of the image. I also worked with Cody to make sure that my illustrator file would be compatible for rastering. I also learned from a classmate that it is useful to sand my product after to clean it up.

## Speculations ##

I think that laser cutting is already a very explored tool. I chose to use it to make a bookmark, and I think in the future it would be helpful to create some sort of software that would predict burn marks on laser cut pieces. Right now I saw that you can predict the time it will take, but I think that predicting burn marks would also be helpful and avoid wasting material.

## Images and write up of laser cut bookmark ##

For my assignment I made a bookmark that can be used for textbooks or reading books. I wanted to make it personal to me, so I put my name on it along with an image of a crown and a dress form. This is because my name means "queen" in Hindi and I like to sew in my free time. I also chose the thinner plywood option so that it would be thin enough that it wouldn't bend book pages. 

![rani_initial](https://github.com/user-attachments/assets/b29765c1-246e-470d-b6d9-486a08e994b1) 
My intial design was just my name with the full spelling and letters. However to make it more interesting, I then added a crown to the top of the R and added the dress form instead of the I.

![illustrator_file](https://github.com/user-attachments/assets/c51cee51-85e8-4c8c-8343-4acd5b7e4310)
This is the updated design. I also added small rectangle cut outs around the edges of the bookmark so that some light can come through.


https://github.com/user-attachments/assets/3303cfda-bf22-4016-864e-a512ea2eb216
Here is a video showing my piece being laser cut. I took longer that expected. In the future and would choose less images to raster so that more light and texture can be added to the piece.

![IMG_4970](https://github.com/user-attachments/assets/781958f3-669c-4c2c-8b5d-ebde55840f3c)
This is the final product. After I cut it, I sanded it to remove some of the burn marks. In the future, I would add more cut outs and more details to the letters. I would also make the hole smaller since a thread does not need to be that big to fit inside it.

# Progress Report 2 #

## Reflections ##

This week, I spent a lot of time working on Grasshopper and Rhino and attempting to figure out how all of the components come together. I played with the cell phone stand file in order to see how adjusting/ deleting the model would impact the final product. I also spent some time diagramming the process of creating the cell phoen stand, so as to help me understand the most efficient and accurate method of designing my own stand.

In terms of what I learned from my during this week, I learned how to create a box from scratch. It was interesting to me to compare what I watched online through various tutorials and what was presented in class. It seems that there are a multitude of ways that one can create a box or ractangular shape and it's a matter of finding what works best for you and what is most intuitive to the rest of the design. Working with my classmates also proved to be immensely helpful; I spent a lot of time troubleshooting replacing the cell phone stand with my own design, and we ended up learning that it is necessary to create a new brep for the new shape we want. I also learned that you can create shapes in Grasshopper using shapes, and so I am excited to potentially try that for the project deliverable.

## Speculations ##

I had never encountered Grasshopper before, and so I was confused as to its usability in comparison to other toold such as Fusion 360, which I find to be easier to navigate. I think from what I understand, Grasshopper will be useful in the future for understanding why and how a 3d model is built. Much like its use now, I can imagine future classrooms implementing Grasshopper in the curriculum so as to provide background and understanidn on 3D modeling tools, regardless of whether its actually used in industry at the time.

For my project, I would love to explore using math equations to create a unique shape. I studied math in my undergrad and so I'd be curious to see how math can intersect with 3D modeling. I also want to find a way to test the balance and stability of the new stand that I create to ensure its usability.


## Diagram ###
For this report, we needed to explore the cell phone stand file and make a diagram to analyze it. I chose to use the cell phone stand with context. 
![IMG_4986](https://github.com/user-attachments/assets/2c5f595d-4cdf-42b5-bb86-780920122a36)

I chose to summarize the context bubbles along with the different components in the grasshopper file. I observed a few main categories in the creation of the cell phone stand: starting with the origin, creating the origian for the stand, designing the stand, changing phone visibility, and baking. I highlighting each of these sections in the diagram below.
![Diagram](https://github.com/user-attachments/assets/f8cfe230-5153-46c5-9698-6e65872bdc56)

## Experimenting with files ##

When I first opened the file, I found that I was only able to easily examine the top view. However, I wanted to add more dimension to it in the Z direction, so I decided to play with the z sliders. Specifically, I changed the center Z and the cylinder void radius. This made the shape fuller and more fun to play with.
![cynlinder](https://github.com/user-attachments/assets/f4e54787-2b53-4b7c-a4cb-a74a5ea2d74f)

I then decided to play with the cell phone parameters and was surprised to encounter warning notes on the file. Because I increased the phone viewing angle too much, the phone to base interface became unstable. Decreasing the sphere 1 radius also seemed to produce similar results. To bring the model back to an acceptible form, I moved the sliders closer to their original range. 
![angle](https://github.com/user-attachments/assets/706696e1-3713-4215-b284-c5f809a94cba)

I also played with the cylinder radius and sphere radius some more to see how it impacts the thickness of the model. I definitely would not continue with this design, but it was worth exploring.

![sphere_modified](https://github.com/user-attachments/assets/1b5e8a5a-ecae-4f6c-a72d-7a0f5498ea00)

Lastly, I tried creating a cube that could potentially replace the sperical base. To do this, I followd the in class demo and that refined it in my own time.

![cube](https://github.com/user-attachments/assets/f69245e4-6cfd-431e-b39a-0be0b327294f)

## Generating Basic Model ##

I struggled with this part, as I am completely new to Grasshopper. I tried to follow a tutorial that explained how to make a box. I got to the 2D stage, but got stuck on adding the Z element. I tried dragging the point in the z direction on Rhino but didn't have any luck.

![newform](https://github.com/user-attachments/assets/55518d12-bcb7-44da-b37e-2cd1e1c475be)

After experimenting more with Grasshopper and following the in class demo for creating a box, I became more comfortable with the software. After playing with the dimensions a bit, I ended up with the following component connections:

![box_components](https://github.com/user-attachments/assets/990a82c8-7c47-403f-a2f5-8da276670015)

The next step was to replace the spherical cell phone base with the box base. I hit a few road blocks along the way while doing this. First I was confused why there were two brep components that connected from the original spherical base to the solid difference component. After disconnecting the components in a few variations, I ended up disconnecting the Brep Cell Phone Stand Base and adding the Brep from my Box design.

![stand_connection](https://github.com/user-attachments/assets/a344ffb0-9ec9-4b96-975f-bc9c7ce22417)

# Progress Report 3 #

## Reflections ##
This week I spent a lot of time going over the computational design system and trying to understand the different parts of it. I found that the best way was to find examples online of different systems being used in real life. In terms of what I learned from my during this week, I learned a lot more of working with Grasshopper and understanding the various components that are involved. I discovered how to create a shape with semi circle shapes and how to inserts holes in a specific aspect of a shape. I spent a lot of time troubleshooting how to create ridges in the shape. I am looking forward to refining my work.

## Speculations ##
						
I think system thinking is helpful in clearly outline a user’s goals and processes towards an end goal, and this is particularly helpful when working in a team to build a product. An engineer has their own goals and system, and so does the designer and marketing team. Through collaborating and iterating on their systems, they can then work towards meeting their collective end goal. In terms of AI, I can see AI playing a greater role in the obersation phase, as AI systems could observe human tendencies as supposed to humans making the obervations.

## Update on Project 1 ##

For my project, I've decided to go for the axolotl level. Grasshopper and Rhino are completely new to me, and I think this would be a good chance to try gain a better understanding of these tools. Because I chose this skill level, I decided that it would not be approporiate to do a cell phone stand. This led me to look into other object ideas. As mentioned above, I was interested in incorporating math equations into my projects - I was a math minor in college and so I thought this would be fun to include. Based on my research, it seems that there are multiple ways that this can be included; Two of the ways I found was to use parametric equations or an expression component with a specific formula. From here, I began experimenting with how this could be converted into an actual product. I brainstormed coaster that included a geometric design, a parametric wall piece for my room, and vases with cool geometric designs. Eventually, I settled on creating a wall planter with parametric designs. 

My first step was to research examples of this design idea, and I found that it actually existed. I found the following 3d printed planter on Etsy, and decided to use it as inspiration with the goal of replicating it. Here the planter is attached to the wall with command strips, but I hope to make planters that have 2 holes on either side of the planter, so that a string go through, making it a hanging piece. 

![etsy_planter](https://github.com/user-attachments/assets/ac3a3525-860e-4389-b726-95e32a990b68)

## This leads me to following knowledge gaps - (1) how do I create a vase like structure that has a parametric design? (2) How do I create a flat backing for the planter so that it sits against the wall? (3) How do I punch holes into the sides of the planter so that it can be hung? I will now attempt to solve these questions:

(1) I found a few tutorials online that discuss building a vase with parametric vases, and so I decided to follow a few of them. This is one vase that I created by multipling circle and using sliders and a Bezier curve to alter the radius and curve of each circle. I found that this create an ideal shape for my object, but I wasn't sure that this would be the best approach to creating the edges and curves in my planter. 
![vase_design](https://github.com/user-attachments/assets/933ad85f-b7cd-4de1-bba9-c0a51e408046)


## Outline of my Video ##

(Time Lapse of me sitting at my desk working/ hanging both planters on the wall/ placing one planter on my desk)

Hi my name is Rani - today I’m going to show you my computational design behind these spiky wall planters.
 										
For this project, I chose level 3, Axolotl. I have never used Rhino or Grasshopper before, and so I thought this would be a good opportunity to challenge myself and become better at 3D modeling. 

Goal:
(1) Create planters that can be hung or placed on the user’s desk (separate videos of large planter hung and planter on desk with flowers)
Challenges: constructing the flat backing
At first tried to split the object in half (show grasshopper video)
but then decided to start with a semi circle arc and build up from there (show grasshopper video)
Solution: flat backing to sit against wall and holes to hang the planters


(2) Give the planters customizable ridge patterns, size, and shape (video of both planters side by side )
Solution: add sliders to the ridge design, width, height, and use a Bezier curve
Challenges: creating ridge design
At first tried to use a polygon component to create multi sided stars (show grasshopper video)
But then decided to use a division component to create pattern (show grasshopper video)
Also added a slider so the user can adjust how spikey the planters are (show grasshopper video)

Other features
Can adjust the width and height/ shape of planter (show grasshopper video)
Minimizes desk space
Minimal time ~ around 3 hours per planter + can hold water				
 														
Conclusion: A concise and effective summary of the project and reflections.						
Overall, I’m pretty happy with the end product. Through designing these planters with adjustable features such as pattern, size, and shape, they become fun additions that optimize the user’s working space.

# Progress Report 4 #

## Reflections ##
This week was not as eventful for me, since we just finished our first project. For the video, I had to spend sometime remember what tools and visual methods are most effective to help teach the viewer about a product. This week we started learning about microcontrollers and coding. I have experience in both, but it was nice to have a refresher. For troubleshooting, I needed to look up more on visualizing ecosystems and converting that into a map. I also had difficuly setting up my Visual Code properly. I'm looking forward to next week and to solving this problem.

## Speculations ##
This week we focused on microcontrollers and our video presentations for our first project. For speculations, I would like to learn more about using Arduinos and different sensors that can be involved. I would be curious to learn more about how AI could interact more with our personal device ecosystem in the next 10 years.

## 9/26: Ecosystem Map ##

For my ecosystem, I decided to analyze my personal device system. For me, this includes my phone and computer. As a first step, I jotted notes on what information and data was shared for each device, and what feedback loops were involved with these pieces of information. I also want to find connection of information and feedback loops that involved both my phone computer.

![IMG_5087](https://github.com/user-attachments/assets/6a75f7bf-b51d-4c65-87f6-1ae374d224e8)

I then translated these notes into a map. In this map, my phone shares information and data in the form of text messages, photos, the notes app, Instagram, and Spotify. My computer shares information and data related to my browser suggestions and email. For feedback systems, I send text messages to people that contains photos, notes, or other information, they send messages back, and this informs the new photos/ notes/ messages that I choose to send in the future. When I choose songs to listen to on Spotify, data is shared regarding my preferences, and this informs new song recommendations in the future. When I scroll on Instagram and click on suggested products that I like, data is stored on my preferences which informs new Insta suggestions. This information also leads me to go on my computer and search such items on my browser. This also informs new brower suggestions on my computer. For email, when I receive a calendar invite on my computer and click "accept," this leads to new emails that are sent in the future to remind me of the upcoming event.

![IMG_5088](https://github.com/user-attachments/assets/b04a9934-466c-4f6b-ad16-2344388eafff)

# Progress Report 5 #

## Reflections ##
This week I spent more time with microcontrollers and using LEDs and buttons. This was somewhat of a refresher for me as I have encountered both in my previous studies. In terms of troubelshooting, I had a difficult time with compiling all of the files that were necessary. To troubleshoot, I consulted people in the maker space and watched tutorials. Next week, I hope to spend more time experimenting with these files.

## Speculations ##
This week we focused on microcontrollers and more coding files. For speculations, I would like to learn more about using the different ways I can make an LED flash. I would be see how flashing lights can be incoporated into different systems an alternative communication method for people.

## Monday 9/30 ##

### Flashing and Experimenting with Make It Blink ###

To make this file compile and flash, I simply copied and pasted its contents into my existing document. Because it was the first time compiling, it took some time to reach a stable blinking state. At the beginning, it flashed a variety of different colors and at different rates. Finally after around 10 seconds, it stabilized to a blue LED light that blinked slowly.

I then wanted to play with changing how quickly the LED blinks. I tried a few different strategies, although I didn't quite achieve my desired result. First, I found the change_period function and adjust the range to be between 50 and 300, in order to reduce the delay between the LED turning on and off.

![change_period](https://github.com/user-attachments/assets/4c2e8f74-ef5d-4050-9437-49ae6072dbcf)

After further analysis of the system, I realized that the function was only used if a button was pressed. From there, I decided to adjust the periodicity variable directly. This appeared to alter the blinking rate; however eventually, the blinking stablizied to its original timing. Lastly, I tried reducing the delay between digitalWrite(led_out, HIGH) and digitalWrite(led_out, LOW) directly in the loop() function. Again, this appeared to work at the beginning, but then the LED eventually stabilized to its original timing. Given that I was unable to achieve my desired effect, I would like to investigate this file more in order to understand what exactly changes the blinking rate. I think this system could benefit from a new design where there is more documentation on how "Hello World" relates to the blinking of LEDs. The benefit of this system is that there is a separate function for pressing a button, thus making it easier to alter what happens when this action is taken. 

### Experimenting with Hello World ###

I also tried working with the Hello World file, which was much simpler than the previous one. My first difficulty came with using the serial monitor. I kept trying to run the code but didn't see any messages appearing in the monitor. Eventually, I realized that I didn't have the monitor set to Particle rather than the Incoming Port. Once I did this, the messages started to appear correctly. 

For my experimentation, I decided to adjust the message from "Hello World!" to "Hello World, my name is Rani!". This updates the serial monitor to include my new message along with the new number of characters in the message, which is 29. 

![hello_world_rani](https://github.com/user-attachments/assets/1aad72b4-21aa-43da-88f2-7afa9199a16a)

This system is a super simple design, so I don't have many suggestions for improving it. One way I could make the system more complex is by having it be interactive. Perhaps the message starts with "Hello World, my name is XXXX," and then the user has to keep typing letters till they can correctly guess the name in the message. When their guess is correct, the system prints a message on the monitor congratulating them on winning the game. 

### Experimenting with Make It Blink Outside ###

I didn't do much with this file except for running it. The system seems to be much more complicated than the previous ones. With further analysis, I'd like to find a way to make it easier to read and interpret for a user that isn't familiar with this structure of code. 

![IMG_5111 2](https://github.com/user-attachments/assets/e05509f1-21cc-473a-8a17-c4c2c25a42ed)

## Thursday 10/3 ##

### One more introductory demo tutorial ###

For my additional demo, I decided to complete the altering periodicity tutorial, which we had started to complete in class on Monday. This session was interesting because we were using a png of an example circuit to learn how to set up our system to run the file. I have worked with circuitry before, but I found this image file to be extra helpful to see exactly where everything is wired in. In the future, I hope to gain better proficiency in understanding why certain components are places where they are.

Image of my circuitry:
![IMG_5119](https://github.com/user-attachments/assets/b4533371-0c92-4e90-8a8d-2cdcd46d128d)

It was excited to have the button working! At first, I wired it and forgot the resistor. After looking closely at the image again, I realizes my mistake and added it in. I do think it's odd that the resistors don't have clear labels to differentiate them, but the resistor I chose worked regardless. Below you can see the serial monitor response to me pressing the button. It gave a message indicating that I pressed the button and then changed the periodicity afterwards.
![button](https://github.com/user-attachments/assets/fbe4420b-a6b1-4939-886d-8b5f3253dca9)

### 3 step-by-step tutorials ###

#### button_led_pulse ####

This tutorial took way longer than I anticipated. I first started by following the circuitry images in the tutorial. One roadblock I encountered was that the button in the tutorial had 4 legs, but the buttons I had only had 2 legs. This maded it harder to interpret how they suggested I circuit the button to the arduino. I began by placeing the button on the left side of the breadboard and connecting a wire on the right side rail of the bottom right leg to the pin D6. After attempting to run the code and having no success, I realized that my wire connecting the bottom leg needed to be on the left side (so that both the button and the connecting wire were located on the same side of bread board). I also needed to flip the LED in order to make it flash. Lastly, I found that it was necessary to alter the code slightly by placing the buttonPressed() function above the setup() function. Below I have a picture of my circuitry while the code is running.

![IMG_5124](https://github.com/user-attachments/assets/b906dc59-75d8-4004-94fb-1722b5fa3454)

To ensure that my button was infact pressing, I also added print statements within the buttonPressed() function and the loop() function to indicate that the button was pressed and a change was occurring.
![buttonpressed](https://github.com/user-attachments/assets/0fc9ae14-4e4b-4650-885e-ef01669d886f)

This project differs from the demo tutorial above in that pressing the button alters an LED rather than the delay periodicity between "Hello World" statements. I do feel that the code could have been further simplied, and that it could use more comments and documentation so that a random person can understand it. In terms of how it could be combined into a larger ecosystem, I think it would be cool to translate this code into morse code, where pressing a button alters that LED to transmit a certain morse code message.

#### fsr_to_ledcolor ####

This tutorial was way easier to follow. I simply circuited my board according to the directions online. The one problem I encountered was not correctly connecting the LED to GND. I thought that you could choose any side of the breadboard as the GND, but then I learned that I have to connect to the side that the arduino is connected to. After altering this, the file worked and correctly altered the color of the LED.

![IMG_5125 2](https://github.com/user-attachments/assets/87452234-5926-491a-8cc5-fa9b2f0318b7)


Work through any 3 of the step-by-step tutorials listed here. Note, as shared in class, that if you choose a tutorial with a servo motor you will need to obtain this from either Sudhu, Fareha, or Baurzhan.
Consider the following:
- how do these demo projects differ from what we've looked at already in the prior examples?
- What are some similarities?
- How might the demonstrations be expanded to include a new feature? What is the feature that would be most relevant to your life?
- Can you imagine the examples being combined into a larger ecosystem? What would that system look like?

#### tutorial 3 ####

    Work through any 3 of the step-by-step tutorials listed here. Note, as shared in class, that if you choose a tutorial with a servo motor you will need to obtain this from either Sudhu, Fareha, or Baurzhan.
Consider the following:
- how do these demo projects differ from what we've looked at already in the prior examples?
- What are some similarities?
- How might the demonstrations be expanded to include a new feature? What is the feature that would be most relevant to your life?
- Can you imagine the examples being combined into a larger ecosystem? What would that system look like?

# Progress Report 6 #

## Reflections ##
This week was eventful, as I spent time soldering and brainstorming for our group project. I have soldered before, but I have never needed to in order to make use of Stemma modules. I found that some of those modules were difficult to understand, especially figuring out what was needed in the wiring. For troubleshooting, I consulted other members in my cohort for help. I'm looking forward to next week to have better understanding of the sensors and tools necessary for Stemma.

## Speculations ##
This week we started brainstorming our group project and looked into using an animatronic penguin. While this isn't directly in the curriculum, I think it is interesting to touch on for further applications. I could see in the future, how more kids would have animatronic stuffed animals that interact with them, rather than normal stuffed toys. I am curious to see whether this develops in the next few years.

## Monday 10/7 ##

The first part of the assignment was to a soldering exercise. Because I have soldered before, it wasn't as challenging to do. The first two attempts were a little messier, and then afterwards I was able to achieve nice and even dots.

![FullSizeRender](https://github.com/user-attachments/assets/29b8937e-18f4-4205-a69d-f9d9d5ba798f)

Downloading the Stemma files and running them proved to be somewhat challenging, as many of the packages weren't installed. I went through the Configure command and tried to look through Particle documentation and other various websites to attempt to install them but found no luck. Eventually, I decided to copy and paste the contents of the Stemma files into the files I already had created that had the packages pre installed. After this, I was able to run the file with the gesture sensor. 

![IMG_5154](https://github.com/user-attachments/assets/dfb92c07-aaed-4a78-8cb1-aa31d4f79920)


## Thursday 10/10 ##

### System 3 ###

For this week, I spent time brainstorming what I wanted to do for the group project. One of my teammates enjoys creating robots and things that move, and the other has interests in P5. I really enjoy working with textiles and wearable products, so we had to think through how we could integrate all of our ideas into one. At first we were thinkng of creating a wearable that could connect heart rate to attraction on a first data. Then we brainstormed other products that could facilitate affection between two people. We came a concept called Penguin pebbling, which is a common form of displaying love for those on the autism spectrum. This led us to come up with an animatronic penguin that can be a means of facilitating affection between two people. 

After solidfying our ideda, we then go to working on our proposal. We decided to use a mechanical 3D printed beak that can open and close to gift a pebble. Other components in our system include an LED to indicate that there is a gift inside the penguin, a servo, a proximity sensor, and a button that the sender presses to trigger the LED. 

![FullSizeRender](https://github.com/user-attachments/assets/f2502d82-1100-43ec-a7a8-aa7d2dac6f25)

Above, we have a sketch of our system and how the different components interact with each other. My main role for the project will be to figure out how to use the Cloud to have the button from the sender trigger the LED on the penguin. 

# Progress Report 7 #

## Reflections ##

I think I performed better than last week. I have some background knowledge working with micro-controllers so I was able to help my teammates troubleshoot how to connect different sensors and edit the associated code. I think I fell behind a little bit on my part of the project, but that was also because my VSCode disconnected from Particle Workbench, which ended up delaying me. I also appreciated how well my project team coordinated with each other. Everyone was good about communicating their progress and were willing to help with aspects of the project that they weren't originally assigned to.

For next steps in my part of the project (connecting the button and LED via the cloud), I plan to connect my code and electronics to my teammate's laptop to see if it works using her VSCode.

## Speculations ##
I think that cloud environments are helpful for understanding the communciation between multiple devices. For speculations I would be curious to see how this is implemented further in communication between networks on Earth and those in Space.

## Project 2 Progress ##

This week, I spent most of my time figuring out how to publish and subscribe a variable through the coud. As my first step, I thought it best to wire the button, and focus on publishing that component to the Particle console. There is a tutorial on github that discusses how to publish such an action to the console, and so I simply followed that. Below there is a picture of my wiring of the button.

![IMG_5189](https://github.com/user-attachments/assets/d3abaa74-d7ac-49cf-bc86-04e1de9c0d20)

After wiring the button, I then cleaned up the file that was given in the tutorial. For the purpose of this project, I needed to press the button and have that signal sent to the console to be retreived by another photon. Here, is where I encountered problems. My file would not flash despite compiling correctly, and the events that were published to the console did not reflect the action of pressing a button. Below is a screenshot of these events.

![console](https://github.com/user-attachments/assets/095da899-03da-4aa9-acd3-e11fe68dd4b0)

# Progress Report 8 #

## Reflections ##
This week was extremely stressful in trying to figure out how to complete our project. I would say I performed better than last week because of the extensive amount of time I put into working on everything. Some of the problem areas I faced included maintaining connection between the photon and the computer and successfully getting the servo to work. To troubleshoot, I consulted our professors and also watched tutorials on the Particle Photon. Next week, I am looking forward to starting on LLMs and wrapping up this project.

## Speculations ##
This week we spent a considerable amount of time troubleshooting the connection between Particle Photon and the computer. For speculations, I think it would be interesting to consider microcontrollers that automatically are registered by computer softwares without any manual addition. This would make working with them much more efficient and useful.

## Thursday 10/24 ##
This week was very busy as we continued working on our project. We faced many challenges, including not being able to correctly attach the servo to beak of the penguin. We also worked on stuffing and de stuffing the penguin the right amount in order to fit the electronics inside correctly. Here is a progress picture of the de stuffed penguin.

![yogurt](https://github.com/user-attachments/assets/da86f7fd-ca1f-4b61-b500-aa307114445c)

Moreover, we realized that we needed to revise our draft diagram to more accurately match with what our project was doing. Below is a picture of the revised diagram.

![draft_diagram](https://github.com/user-attachments/assets/15a2cb41-cc5a-483e-b8d8-56aa4561f999)

We only partially figured out how to pur everything together, and encountered many issues with connecting the device to the Cloud. We needed to reset the photons multiple times, which proved to be extremely frustrating. Evnetually, we figured out that this could be sorted by simply using the VSCode of another cohort member. After figuring this out, we then got to creating our video. We included an animated introduction that explained Pebble's purpose. Below is an animated slide that talks about what penguin pebbling is.

![Gifts3](https://github.com/user-attachments/assets/ece3b11f-b371-4566-93be-61582e12bab4)


# Progress Report 9 #

## Reflections ##
This week was much more relaxing compared to past ones, so I don't have too much to reflect on here! I would say our cohort performed well/ the same as usual haha. Something I thought was nice was that during class when there was confusion on how LLMs function, many members put explanatory videos and articles in our group chat to help. Looking towards our project next week, I hope we can continue working together to understand the various components in the project. I think I performed less than last week, but that's mostly because we had way less to do. I spent time working on my project report and received assistance from my teammates while also giving my input, as well. Next week I hope to spend more time on class material. This week was dedicated to recovering from late nights working on project 2, but now I feel more rested and ready to tackle the new material.

## Speculations ##
I would speculate that LLMS could be interesting when interacting with each other. Right now we are building a singular LLM that does something on its own. I would be curious to see in the future, whether LLMs could "consult" each other, without the user specifying it. I'm also wondering if in the future there will be any sort of regulation on what data LLMs will have access to.

## Thursday 10/31 ##

For this week, we spent a lot of time working on zerowidth tutorials. I have never worked with LLMs Chat GPT models before, so this was an interesting exercise for me. First, I used th in class tutorial to get familiarized with the environment. I found that it was easy to navigated and not too difficult to understand. I also found that the modeling features matched up with Grasshopper. Below is a picture of E1, where I simply dragged components to create an initial model.
![E1](https://github.com/user-attachments/assets/e5028f90-6c27-4219-be89-4246915cfc4f)

After going through E2, I then got to add knowledge to the knowledge base. Ths was interesting to take data from this very weekly report as an information source for the model. I found that the accuracy was great depending on the questions that I asked. I think in the future it would be nice to adjust the chunk size or other features to improve this. Below is a screenshot of my E3. 
![E3](https://github.com/user-attachments/assets/18ce3236-6690-47e0-bbfb-d7de4bb5d1bb)


# Progress Report 10 #

# Progress Report 11 #
....
****
---
