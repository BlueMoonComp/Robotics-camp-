# Servo Walker Project 
## Introduction
> #### Servo Walker 
> Before a person can learn to walk, they usually crawl. That's what the main function of what the Servo Walker does, which is crawling with its front two legs, or in this case blocks. And conveniently, that is what we are going to create in this project!

---

> #### What Will I Learn?
> This project will teach you how to create a simple moving, yet stationary robot using a servomotor and a small amount of parts.

---

> #### The Main Purpose Of Building This Robot:
> As you continue to build more robots in this workshop, you will learn how building stationary robots prepars you to build robots that move by directed actions or self-programming.

---

## Activity 1
### Building the ServoWalker!
Before building the robot, we need to go over a few things about the motor we will be using, which is called a **servomotor**. There is a wide and narrow side of the motor, it's important we know which side is which, or we will end up building it wrong! 

![ServoMotor Image](./ServoMotor_Snippet.JPG)

> ### Fun Fact
> Servomotors are usually refered to as "servos" and they play a big part in radio-controlled airplanes, like helping to position control surfaces like elevators to help with elevation and rudders to help turn the aircraft!



### What you need to build:
> * Studuino Unit
> * Battery Box
> * USB Cable
> * 4 Light Aqua Blocks
> * 4 Aqua Blocks
> * 2 Servomotors
> ### Note that the colors of the blocks don't really matter, just make sure you have the right amount of what ever color block you choose.

---

### 1
Start by making two sets of the blocks shown below.
![](./1.JPG)

### 2 
As shown below, add the **D10 Servomotor** to one set of the blocks you created in the previous step.
![](./2.JPG)

### 3 
Add the **D9 Servomotor** to the remaining set of blocks as shown.
![](./3.JPG)

### 4 
Assemble the parts as shown in the image.

![](./4.JPG)

### 5 
Insert the cables for the **D9 and D10 Servomotors** into the ports shown on the circuit board.
![](./5.JPG)

### 6 
Now add the **battery box**.

![](./6.JPG)

### 7 
This is what your completed robot should resemble.
![](./7.JPG)

## Great Job Ninja!
You have mastered the art of creating your very own Servo Walker! Continue on to your next activity lesson!

## Activity 2
### Coding The Walker 
Now it's time to code your Servo Walker! Connect your USB to the computer and open Studuino. Select the **Block Programming Environment,** then select the **Robots** tab to transfer code that you'll make to the robot you built!
![](./code1One.JPG)
![](./code2Two.JPG)

### 1
Go to the **edit** menu and select **Port Settings** from the drop-down. 
![](./code3Three.JPG)

### 2 
Make sure that you **Check all of the boxes that are checked below**. Then click **ok**.
![](./code4Four.JPG)

### 3 
Once you're done with the port settings, your screen should look like this.
![](./code5.JPG)

### 4 
The next thing you'll want to do is go into the **motion menu** on the left hand side of the screen and drag out the **set servomotor block** onto the coding area. You'll want to do it a few times to where your screen looks like the one below. These blocks change the angle that the servomotor moves to, which makes it move from one side to the other.

![](./code6.JPG)

### 5
For this step, we'll **focus only on the code blocks that are set to the D9 servomotor**. Change the degrees in that block to the numbers below.

![](./code7.JPG)


### 6 
For this step we'll **focus only on the code blocks that are set to the D10 servomotor**. Change the degrees in that block tot he numbers below.

![](./code8.JPG)

### 7 
Now, we're going to **go into the control menu**, which is located right next to the motion menu in an orange color. Once we're in the menu, you'll see a **wait block**. Wait blocks are used in code to tell what ever you're coding to wait a certain amount of time before preforming another statement! We want to **grab 7** of those and **change the number inside from 1 second to .08 seconds**, like in the picture below.
![](./code9.JPG)

### 8
Finally, we're going to combine all of the code we've made so far into one big block of code! Here's a picture to help put it in order. The **forever loop** that is surrounding all of the code in the picture is used to tell the robot that as long as the program is running, run that code **forever** until we tell the robot to stop.
![](./code10.JPG)

### 9 
Now it's time to transfer the code you made to the robot you also made! Make sure that the **USB cable is connecting the computer to the studuino unit**, then click on the run button, and a drop down menu will come up that has the word **Transfer** on it, click on that and the code will transfer to your robot! 
![](./code11.JPG)
## Congradulations! You built and programmed a ServoWalker!

> ### Knowledge test
> What is a **for loop**?

