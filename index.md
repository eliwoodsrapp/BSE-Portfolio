# Ball-Tracking Robot
This Raspberry Pi-powered robot uses a camera module to detect and approach a ball. The trick is in the color: the Raspberry Pi isolates the color of the ball, making identification much more simple.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eli R. | Irvine High School | Mechanical Engineering | Incoming Senior

![Headstone Image](https://bluestampengineering.com/wp-content/uploads/2016/05/improve.jpg)
  
# Final Milestone
My final milestone is the increased reliability and accuracy of my robot. I ameliorated the sagging and fixed the reliability of the finger. As discussed in my second milestone, the arm sags because of weight. I put in a block of wood at the base to hold up the upper arm; this has reverberating positive effects throughout the arm. I also realized that the forearm was getting disconnected from the elbow servo’s horn because of the weight stress on the joint. Now, I make sure to constantly tighten the screws at that joint. 

[![Final Milestone](https://res.cloudinary.com/marcomontalbano/image/upload/v1612573869/video_to_markdown/images/youtube--F7M7imOVGug-c05b58ac6eb4c4700831b2b3070cd403.jpg )](https://www.youtube.com/watch?v=F7M7imOVGug&feature=emb_logo "Final Milestone"){:target="_blank" rel="noopener"}

# Second Milestone
For my second milestone, I developed the car module itself, and programmed it to avoid objects. First, I assembled the car module kit, including the chassis, motors, wheels, and battery pack. I secured my Raspberry pi and an H-bridge to the chassis, as well as three ultrasonic sensors, and then I wired together all neccesary devices. The battery pack did not produce the correct voltage to power the pi, and I would end up using an alternative power source, but for this milestone, it stayed connected to its charging cable. Once everything was in place, I set to programming. I tested the motors (using pwm) and the ultrasonic sensors respectively, before I tried to program obstacle avoidance. Both tests went well, but obstacle avoidance proved tricky. The logic I used had the motors randomly stopping and glitching. Finally, by playing around with delays and the duty cycle for the pwm, I got the code to work. It was nice to complete such a large part of the finished prototype.

<iframe width="967" height="544" src="https://www.youtube.com/embed/yA27pY_MWKo?list=PLe-u_DjFx7eujQBN2E6SXTYd1A-A5wa6Z" title="Eli R Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone
  
For my first milestone, I tested the camera module with a color-filter. First, I set up my Raspberry Pi. I uploaded an OS for the Pi to a micro SD, and plugged it into the board. Then, I downloaded PuTTY and VNC Viewer to interact with the Pi through my laptop. Once I could access the Pi, I installed necessary camera packages to be able to use the camera module, then I installed OpenCV for the capability of color-filtering. I plugged in the camera module, and set to writing some test code. The completed code provided three displays, a preview of the raw camera stream, that same camera stream with the color red isolated as white, and finally, the camera stream with the color red isolated as red. It encouraged me, because the test showed a major part of the completed prototype in a functional state.

<iframe width="967" height="544" src="https://www.youtube.com/embed/akWSVJHWgVM?list=PLe-u_DjFx7eujQBN2E6SXTYd1A-A5wa6Z" title="Eli R Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
