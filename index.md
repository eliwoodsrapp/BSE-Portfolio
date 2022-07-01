# Ball-Tracking Robot
This Raspberry Pi-powered robot uses a camera module to detect and approach a ball. The trick is in the ball's color: the Raspberry Pi isolates the color of the ball, making identification much more simple.

| **Engineer** | **School** | **Area of Interest** | **Grade** |
|:--:|:--:|:--:|:--:|
| Eli R. | Irvine High School | Mechanical Engineering | Incoming Senior

![dfgdfg](https://user-images.githubusercontent.com/107571947/176932379-5ec63f23-1e41-4014-81a9-59ca7fbfbe03.PNG)
  
# Demo Night

<iframe width="967" height="544" src="https://www.youtube.com/embed/r0EVvnOVzFQ?list=PLe-u_DjFx7eujQBN2E6SXTYd1A-A5wa6Z" title="Eli R Demo Night" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Final Milestone
For my final milestone, I added the camera to the car, and re-programmed the robot for ball tracking. First, I secured the camera. I also secured a portable phone charger to the robot, which had the correct voltage to power the Pi, finally giving my robot mobility. Then, I worked on the code. Programming was difficult, and I ran into some trouble getting all the code to work. Once it worked, I still had to fine-tune the logic, which was just trial and error. Once it was all finished though, the robot worked surprisingly well.

<iframe width="967" height="544" src="https://www.youtube.com/embed/EPnFZ90-Yls?list=PLe-u_DjFx7eujQBN2E6SXTYd1A-A5wa6Z" title="Eli R Milestone 3" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Second Milestone
For my second milestone, I developed the car module itself, and programmed it to avoid objects. First, I assembled the car module kit, including the chassis, motors, wheels, and battery pack. I secured my Raspberry pi and an H-bridge to the chassis, as well as three ultrasonic sensors, and then I wired together all neccesary devices. The battery pack did not produce the correct voltage to power the pi, and I would end up using an alternative power source, but for this milestone, it stayed connected to its charging cable. Once everything was in place, I set to programming. I tested the motors (using pwm) and the ultrasonic sensors respectively, before I tried to program obstacle avoidance. Both tests went well, but obstacle avoidance proved tricky. The logic I used had the motors randomly stopping and glitching. Finally, by playing around with delays and the duty cycle for the pwm, I got the code to work. It was nice to complete such a large part of the finished prototype.

<iframe width="967" height="544" src="https://www.youtube.com/embed/yA27pY_MWKo?list=PLe-u_DjFx7eujQBN2E6SXTYd1A-A5wa6Z" title="Eli R Milestone 2" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# First Milestone
  
For my first milestone, I tested the camera module with a color-filter. First, I set up my Raspberry Pi. I uploaded an OS for the Pi to a micro SD, and plugged it into the board. Then, I downloaded PuTTY and VNC Viewer to interact with the Pi through my laptop. Once I could access the Pi, I installed necessary camera packages to be able to use the camera module, then I installed OpenCV for the capability of color-filtering. I plugged in the camera module, and set to writing some test code. The completed code provided three displays, a preview of the raw camera stream, that same camera stream with the color red isolated as white, and finally, the camera stream with the color red isolated as red. It encouraged me, because the test showed a major part of the completed prototype in a functional state.

<iframe width="967" height="544" src="https://www.youtube.com/embed/akWSVJHWgVM?list=PLe-u_DjFx7eujQBN2E6SXTYd1A-A5wa6Z" title="Eli R Milestone 1" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

# Schematic

![302_schem](https://user-images.githubusercontent.com/107571947/176756968-4bae23b3-29cc-46bf-9844-8a8d40c543f2.jpg)

# Bill of Materials

|:--:|:--:|:--:|:--:|:--:|:--:|
| Part | Qty | Description | Ref. Designator | Cost | Site
|:--:|:--:|:--:|:--:|:--:|:--:|
| Robot Kit | 1 | chassis, battery pack, DC motors, wheels, ect. | M1,M2 | 18.99 | [amazon](https://www.amazon.com/perseids-Chassis-Encoder-Wheels-Battery/dp/B07DNYQ3PX/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Ping Sensors | 1 | ultrasonic sensors |  | 12.99 | [amazon](https://www.amazon.com/ELEGOO-HC-SR04-Ultrasonic-Distance-MEGA2560/dp/B01COSN7O6/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| H-Bridges | 1 | to control DC motors | IC1 | 8.99 | [amazon](https://www.amazon.com/ACEIRMC-Stepper-Controller-2-5-12V-H-Bridge/dp/B0923VMKSZ/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Pi Cam | 1 | Pi Cam |  | 9.99 | [amazon](https://www.amazon.com/Arducam-Megapixels-Sensor-OV5647-Raspberry/dp/B012V1HEP4/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Jumper Wires | 1 | Jumper Wires |  | 6.98 | [amazon](https://www.amazon.com/Elegoo-EL-CP-004-Multicolored-Breadboard-arduino/dp/B01EV70C78/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Raspberry Pi 4 | Q1 | microcontroller |  | 129.99 | [amazon](https://www.amazon.com/Raspberry-Model-2019-Quad-Bluetooth/dp/B07TD42S27/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Micro Sd | 1 | for Raspberry Pi OS |  | 8.00 | [amazon](https://www.amazon.com/gp/product/B089VVP61W/ref=ppx_yo_dt_b_search_asin_title?ie=UTF8&psc=1)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Raspberry Pi Charger | 1 | stationary power |  | 7.99 | [amazon](https://www.amazon.com/Replacement-Raspberry-Pi-4-Supply-Charger-Adapter/dp/B094J8TK61/)
|:--:|:--:|:--:|:--:|:--:|:--:|
| Cell Phone Power Bank | 1 | mobile power |  | 17.97 | [amazon](https://www.amazon.com/Anker-PowerCore-Ultra-Compact-High-Speed-Technology/dp/B01CU1EC6Y?th=1)

# Tools Required

|:--:|:--:|:--:|
| Tool | Cost | Site
|:--:|:--:|:--:|
| Soldering Iron | 19.99 | [amazon](https://www.amazon.com/Soldering-Kit-Temperature-Desoldering-Electronics/dp/B07GTGGLXN/ref=asc_df_B07GTGGLXN/?tag=hyprod-20&linkCode=df0&hvadid=241999416883&hvpos=&hvnetw=g&hvrand=137463208067721732&hvpone=&hvptwo=&hvqmt=&hvdev=c&hvdvcmdl=&hvlocint=&hvlocphy=9031525&hvtargid=pla-590653449503&psc=1)
|:--:|:--:|:--:|
| Screwdriver Kit | 5.94 | [amazon](https://www.amazon.com/Small-Screwdriver-Set-Mini-Magnetic/dp/B08RYXKJW9/)

# Final Code

```c++
import cv2
import numpy as np
from picamera2 import Picamera2
import RPi.GPIO as GPIO
import time

GPIO.setwarnings(False)

GPIO.setmode(GPIO.BCM)
#ultrasonics
LEFT_TRIGGER = 26
LEFT_ECHO = 6
FRONT_TRIGGER = 5
FRONT_ECHO = 25
RIGHT_TRIGGER = 4
RIGHT_ECHO = 27
#motors
rf = 13 #right forward
rr = 19 #right reverse
lf = 12 #left forward
lr = 18 #left reverse
#ultrasonics
GPIO.setup(LEFT_TRIGGER, GPIO.OUT)
GPIO.setup(LEFT_ECHO, GPIO.IN)
GPIO.setup(FRONT_TRIGGER, GPIO.OUT)
GPIO.setup(FRONT_ECHO, GPIO.IN)
GPIO.setup(RIGHT_TRIGGER, GPIO.OUT)
GPIO.setup(RIGHT_ECHO, GPIO.IN)
#motors
GPIO.setup(rf,GPIO.OUT)
GPIO.setup(rr,GPIO.OUT)
GPIO.setup(lf,GPIO.OUT)
GPIO.setup(lr,GPIO.OUT)
#motor pwm frequency
prf = GPIO.PWM(rf,25)
prr = GPIO.PWM(rr,25)
plf = GPIO.PWM(lf,25)
plr = GPIO.PWM(lr,25)

# using LEFT ultrasonic
def ldistance():

    GPIO.output(LEFT_TRIGGER, True)  # Flash trigger
    time.sleep(0.00001)
    GPIO.output(LEFT_TRIGGER, False)

    StartTime = time.time() # define start/stop time
    StopTime = time.time()
    StopTime = time.time()
    # save start time
    while GPIO.input(LEFT_ECHO) == 0:
        StartTime = time.time()
    # save stop time
    while GPIO.input(LEFT_ECHO) == 1:
        StopTime = time.time()

    TimeElapsed = StopTime - StartTime

    ldistance = (TimeElapsed * 34300) / 2

    return ldistance
# using FRONT ultrasonic
def fdistance():

    GPIO.output(FRONT_TRIGGER, True)  # Flash trigger
    time.sleep(0.00001)
    GPIO.output(FRONT_TRIGGER, False)

    StartTime = time.time() # define start/stop time
    StopTime = time.time()
    # save start time
    while GPIO.input(FRONT_ECHO) == 0:
        StartTime = time.time()
    # save stop time
    while GPIO.input(FRONT_ECHO) == 1:
        StopTime = time.time()

    TimeElapsed = StopTime - StartTime

    fdistance = (TimeElapsed * 34300) / 2

    return fdistance
# using RIGHT ultrasonic
def rdistance():

    GPIO.output(RIGHT_TRIGGER, True)  # Flash trigger
    time.sleep(0.00001)
    GPIO.output(RIGHT_TRIGGER, False)

    StartTime = time.time() # define start/stop time
    StopTime = time.time()
    # save start time
    # save start time
    while GPIO.input(RIGHT_ECHO) == 0:
        StartTime = time.time()
    # save stop time
    while GPIO.input(RIGHT_ECHO) == 1:
        StopTime = time.time()

    TimeElapsed = StopTime - StartTime

    rdistance = (TimeElapsed * 34300) / 2

    return rdistance

def stop():
    prf.ChangeDutyCycle(0)
    plf.ChangeDutyCycle(0)
    prr.ChangeDutyCycle(0)
    plr.ChangeDutyCycle(0)

def forward():
    prf.ChangeDutyCycle(40)
    plf.ChangeDutyCycle(40)
    prr.ChangeDutyCycle(0)
    plr.ChangeDutyCycle(0)

def left():
    prf.ChangeDutyCycle(40)
    plf.ChangeDutyCycle(0)
    prr.ChangeDutyCycle(0)
    plr.ChangeDutyCycle(40)

def right():
    prf.ChangeDutyCycle(0)
    plf.ChangeDutyCycle(40)
    prr.ChangeDutyCycle(40)
    plr.ChangeDutyCycle(0)
#Image analysis work
def segment_colour(frame):    #returns only the red colors in the frame
    hsv_roi =  cv2.cvtColor(frame, cv2.COLOR_BGR2HSV)
    mask_1 = cv2.inRange(hsv_roi, np.array([160, 160,10]), np.array([190,255,255]))
    ycr_roi=cv2.cvtColor(frame,cv2.COLOR_BGR2YCR_CB)
    mask_2=cv2.inRange(ycr_roi, np.array((0.,165.,0.)), np.array((255.,255.,255.)))

    mask = mask_1 | mask_2
    kern_dilate = np.ones((8,8),np.uint8)
    kern_erode  = np.ones((3,3),np.uint8)
    mask= cv2.erode(mask,kern_erode)      #Eroding
    mask=cv2.dilate(mask,kern_dilate)     #Dilating
#    cv2.imshow('mask',mask)
    return mask

def find_blob(blob):
    largest_contour=0
    cont_index=0
    contours, hierarchy = cv2.findContours(blob, cv2.RETR_CCOMP, cv2.CHAIN_APPROX_SIMPLE)
    for idx, contour in enumerate(contours):
        area=cv2.contourArea(contour)
        if (area >largest_contour) :
            largest_contour=area

            cont_index=idx

    r=(0,0,2,2)
    if len(contours) > 0:
        r = cv2.boundingRect(contours[cont_index])

    return r,largest_contour
#start pwm
prf.start(0)
plf.start(0)
prr.start(0)
plr.start(0)
#CAMERA CAPTURE
#initialize the camera and grab a reference to the raw camera capture
cv2.startWindowThread()
picam2 = Picamera2()
config = picam2.preview_configuration(main={"size": (320, 240), "format": "RGB888"})
picam2.configure(config)
picam2.start()
# allow the camera to warmup
time.sleep(0.001)
# capture frames from the camera
while True:
    try:
        frame = picam2.capture_array()
        centre_x = 0.
        centre_y = 0.
        hsv1 = cv2.cvtColor(frame, cv2.COLOR_RGB2HSV)
        mask_red=segment_colour(frame)      #masking red the frame
        loct,area=find_blob(mask_red)

        x, y, w, h = loct

        distf = fdistance()
        distr = rdistance()
        distl = ldistance()

        if (w*h) < 80:
            found=0
        else:
            found=1
            simg2 = cv2.rectangle(frame, (x,y), (x+w,y+h), 255,2)
            centre_x=x+((w)/2)
            centre_y=y+((h)/2)
            cv2.circle(frame,(int(centre_x),int(centre_y)),3,(0,110,255),-1)
            centre_x-=160
            centre_y=120--centre_y
        initial=20000
        flag=0
        if(found==0):
            print('looking...')
            if flag==0:
                left()
                time.sleep(.2)
            else:
                right()
                time.sleep(.2)

        elif(found==1):
            if(area<initial):
                if(distf<10):
                    print('manuvering')
                        #obstacle is encountered
                    if distr>=8:
                        right()
                        time.sleep(0.5)
                        stop()
                        time.sleep(0.5)
                        forward()
                        time.sleep(0.5)
                        stop()
                        time.sleep(0.5)
                        left()
                        time.sleep(0.5)
                    elif distancel>=8:
                        left()
                        time.sleep(0.5)
                        stop()
                        time.sleep(0.5)
                        forward()
                        time.sleep(0.5)
                        stop()
                        time.sleep(0.5)
                        right()
                        time.sleep(0.5)
                        stop()
                        time.sleep(0.5)
                    else:
                        right()
                        time.sleep(0.5)
                elif(centre_x<=-30 or centre_x>=30):
                    if(centre_x<0):
                        flag=0
                        right()
                        time.sleep(0.1)
                        stop()
                        time.sleep(0.1)
                    else:
                        flag=1
                        left()
                        time.sleep(0.1)
                        stop()
                        time.sleep(0.1)
                else:
                    forward()
                    time.sleep(0.5)
            else:
                print('object found')
                stop()
                time.sleep(1)

#        cv2.imshow("draw",frame)

    except KeyboardInterrupt:
        GPIO.cleanup() #free all the GPIO pins
        break

```
