# Block Thrower Project
## Introduction
> #### Block Thrower
> Catapults have been used a lot throughout history, whether it be for defending a castle or lauching a watermelon at a target! They're typically made out of wood and rope, but then one you're about to build is going to be way more advanced than that.
> ### Fun Fact
> The first ever recorded catapult was built in 400 BC!

---

> #### What Will I Learn?
> This project will teach you how to build a robot into a catapult! Not only does it throw objects, but it will have the ability to detect if there is an object to throw!

---

> #### The Main Purpose Of Building This Robot:
> You've already built a robot that moves its legs, so now it's time to build a robot that can throw objects! This is done by using an attached sensor that will let the robot sense whether there is an object ready to be thrown.

---

## Activity 1
### Building the Block Thrower
Once again, before using the servomotor, make sure you know which side is which. This can be done by recognizing which side is narrow, and which side is wide. This image below you can help you recognize the sides.
![](./1.JPG)

### What You Need To Build:
> * 2 Aqua Blocks
> * 2 Light Aqua Blocks
> * 7 White Blocks
> * Blue LED Light
> * Light Sensor
> * 2 Sensor Cables 
> * Studuino Unit 
> * Battery Box 
> * USB Cord
> ### Note that the colors of the blocks don't really matter, just make sure you have the right amount of what ever color block you choose.

---

### 1
Assemble the blocks as shown.

![](./2.JPG)

### 2 
Using the image below as a guide, add the **Servomotor** to the part you built in the previous step.
![](./3.JPG)

### 3 
Now add the part to the circuit borad, AKA the studuino unit.
![](./4.JPG)

### 4
Connect the **sensor cable** to the **light sensor**. Add 3 white blocks, or which ever color blocks you chose to the **light sensor**, as shown below.

![](./5.JPG)

### 5 
Connect the **sensor cable** to the **Blue LED**. Add 3 more white or which ever color blocks you chose to the **LED** as shown below.

![](./6.JPG)

### 6
Connect the parts from step 4 and 5 to create a new part.
![](./7.JPG)

### 7
Next, connect the parts from step 3 and 6 as shown below.
![](./8.JPG)

### 8 
Now insert the cables. Make sure that hey grey wire is facing the center, or else it won't work properly.
![](./9.JPG)

### 9 
This is what the should look like.

![](./10.JPG)

## Great Job Ninja!
You have mastered the art of creating your very own Block Thrower! Continue on to your next activity lesson!

## Activity 2
### Coding The Block Thrower 
Now it's time to code your Block Thrower! Connect your USB to the computer and open Studuino. Select the **Block Programming Environment,** then select the **Robots** tab to transfer code that you'll make to the robot you built!
![](./code1One.JPG)
![](./code2Two.JPG)

### 1
Go to the **edit** menu and select **Port Settings** from the drop-down. 
![](./code3Three.JPG)

### 2 
This picture below will pop up after clicking the **port settings**. Make sure that you check all of the boxes that are checked in the picture below. Also, make sure that the icons next to the checked boxes match also, like the **A4 matches with the LED, A5 matches with the buzzer, and A6 and A7 match with light sensor.**
![](./code1.JPG)

### 3 
Our first code will actually be a function called **BlueBlock.** A function in code is a named group of statements, or blocks of code in this case, that preform a specific task. The **BlueBlock** functions specific task is going to be to activate the catapult! So we'll need to go into the **control menu** and pick out the function block. It'll be blank, so click in the blank spot and click the **new** button and type **BlueBlock**. After that, we'll need to go into the **motion menu** and get our **LED** block. Then go into **control** again and pull out a **wait block** and leave it at 1 second. After that, go back into the **motion menu** and grab the **set servomotor D9 to 90** block. You'll put those all together like in the picture below. This will be your fist function for the robot!
![](./code2.JPG)

### 4
Next, we're going to set up our **conditional statements**. Conditionals in code are statements that depend on a certain event to occur to move onto the code after that conditional. The first conditional that we will be using is to see if the **light sensor** on the robot detects a value **less than** 50 **OR** the light sensor **equals** 30. If either of those events are true, then we will call, or activate the **BlueBlock** function that you made. Make sure that your code matches the code in the picture below. I broke down the first image to help you understand how to build the code to look like the final image.
![](./code3.JPG)
![](./code4.JPG)
