# CircuitPython
This repository will actually serve as a aid to help you get started with your own template.  You should copy the raw form of this readme into your own, and use this template to write your own.  If you want to draw inspiration from other classmates, feel free to check [this directory of all students!](https://github.com/chssigma/Class_Accounts).
## Table of Contents
* [Table of Contents](#TableOfContents)
* [Hello_CircuitPython](#Hello_CircuitPython)
* [CircuitPython_Servo](#CircuitPython_Servo)
* [CircuitPython_LCD](#CircuitPython_LCD)
* [NextAssignmentGoesHere](#NextAssignment)
---

## Hello_CircuitPython

### Description & Code
Hello all! this is my long awaited descriptions on stuff I did nearly 5-6 months ago
I'll admit I am embarassingly late to the party, but at least it ain't june yet!

This is where I Learned how to write Engineering notebooks and the "Hello World!" stuff


Here's how you make code look like code:

```python
from time import sleep

while True:
    print("Hello world!")
    print("Hello world! Atticus rocks!")
    sleep(1)

```


### Evidence


![spinningMetro_Optimized](https://user-images.githubusercontent.com/54641488/192549584-18285130-2e3b-4631-8005-0792c2942f73.gif)


And here is how you should give image credit to someone, if you use their work:

Image credit goes to [Rick A](https://www.youtube.com/watch?v=dQw4w9WgXcQ&scrlybrkr=8931d0bc)



### Wiring
Make an account with your google ID at [tinkercad.com](https://www.tinkercad.com/learn/circuits), and use "TinkerCad Circuits to make a wiring diagram."  It's really easy!  
Then post an image here.   [here's a quick tutorial for all markdown code, like making links](https://guides.github.com/features/mastering-markdown/)

### Reflection
I wish I would've gotten this WAY sooner, but learning is learning.




## CircuitPython_Servo

### Description & Code
Eons ago, back in september, I was working on a servo and what came out was a servo that kinda moved.

```python
Code goes here

```

### Evidence

Pictures / Gifs of your work should go here.  You need to communicate what your thing does.

### Wiring

### Reflection




## Me and Franklin's Paper Airplane arm

### Description & Code

```python
Code goes here

```

### Evidence
![image](https://user-images.githubusercontent.com/71350043/236498198-c26c49a2-c98c-4c99-8404-7e8c44f5881a.png)


### Wiring

### Reflection
Paper Airplane thrower is the best idea ever, oh and this is one accomplishment I'm proud of in engineering




## Sensor Car PID

### Description & Code
This is the current WIP that we're cooking up, while as I write this we are still waiting for Franklin's share of the Motor and Sensor code (Between you and me, if he does not come on monday, imma just do it for him.)

```python
This code is for when the Motor and sensor is introduced
from simple_pid import PID
pid = PID(1, 0.1, 0.05, setpoint=1)

# Assume we have a system we want to control in controlled_system
v = controlled_system.update(0)

while True:
    # Compute new output from the PID according to the systems current value
    control = pid(v)
    
    # Feed the PID output to the system and get its current value
    v = controlled_system.update(control)
Final Product
WIP
```

### Evidence

### Wiring

### Reflection
This was kind of the biggest learning experiences in Engineering I've learned thus far.
