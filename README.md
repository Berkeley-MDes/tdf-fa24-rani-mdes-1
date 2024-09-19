# Hello DES INV 202 Student!
Welcome to your new GitHub repository! 

# Outline
[week 1](README.md#Progress-Report-1)

[week 2](README.md#Progress-Report-2)

[week 3](README.md#Progress-Report-3)

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

## Update on Project 1 ##

For my project, I've decided to go for the axolotl level. Grasshopper and Rhino are completely new to me, and I think this would be a good chance to try gain a better understanding of these tools. Because I chose this skill level, I decided that it would not be approporiate to do a cell phone stand. This led me to look into other object ideas. As mentioned above, I was interested in incorporating math equations into my projects - I was a math minor in college and so I thought this would be fun to include. Based on my research, it seems that there are multiple ways that this can be included; Two of the ways I found was to use parametric equations or an expression component with a specific formula. From here, I began experimenting with how this could be converted into an actual product. I brainstormed coaster that included a geometric design, a parametric wall piece for my room, and vases with cool geometric designs. Eventually, I settled on creating a wall planter with parametric designs. 

My first step was to research examples of this design idea, and I found that it actually existed. I found the following 3d printed planter on Etsy, and decided to use it as inspiration with the goal of replicating it. Here the planter is attached to the wall with command strips, but I hope to make planters that have 2 holes on either side of the planter, so that a string go through, making it a hanging piece. 

![etsy_planter](https://github.com/user-attachments/assets/ac3a3525-860e-4389-b726-95e32a990b68)

## This leads me to following knowledge gaps - (1) how do I create a vase like structure that has a parametric design? (2) How do I create a flat backing for the planter so that it sits against the wall? (3) How do I punch holes into the sides of the planter so that it can be hung? I will now attempt to solve these questions:

(1) I found a few tutorials online that discuss building a vase with parametric vases, and so I decided to follow a few of them. This is one vase that I created by multipling circle and using sliders and a Bezier curve to alter the radius and curve of each circle. I found that this create an ideal shape for my object, but I wasn't sure that this would be the best approach to creating the edges and curves in my planter. 
![vase_design](https://github.com/user-attachments/assets/933ad85f-b7cd-4de1-bba9-c0a51e408046)

I then decided to try another parametric vase tutorial that uses a rich graph mapper. 

Title Page
 								
Your name: Rani Sheth
Your project title: Spiky Wall Planters

Project Challenge Level Rationale



(Time Lapse of me sitting at my desk working/ hanging both planters on the wall/ placing one planter on my desk)

Hi my name is Rani - today I’m going to show you my computational design behind these spiky wall planters.
 										
For this project, I chose level 3, Axolotl. I have never used Rhino or Grasshopper before, and so I thought this would be a good opportunity to challenge myself and become better at 3D modeling. 

Diagrammatic Analysis of your System: At least one diagrammatic analysis of the system you have used for producing your cell phone stand.


My user is a busy student that wants flexibility in decorating their room. ****** 								
Project Challenge Results

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

 									

Prototype Demonstration: Document/Demonstrate (in the form of photos) your prototype, a working cell phone stand or chosen object.
 							
 														
Speculations: Your speculations on the impact of systems thinking and computational design tools: written, sketched and described, and or storyboards (open to interpretation):
 								
I think system thinking is helpful in clearly outline a user’s goals and processes towards an end goal, and this is particularly helpful when working in a team to build a product.

An engineer has their own goals and system, and so does the designer and marketing team (	animation)

Through collaborating and iterating on their systems, they can then work towards meeting their collective end goal (spiral animation)
										
 									
Conclusion: A concise and effective summary of the project and reflections.
 							
Overall, I’m pretty happy with the end product. Through designing these planters with adjustable features such as pattern, size, and shape, they become fun additions that optimize the user’s working space.
				





---
