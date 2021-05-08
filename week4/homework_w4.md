# Homework for Week X

## Task – Hold Your Note

### Software Requirement

* After press button A, your micro:bit should start a new game. 
* If micro:bit detects your voice, it will start counting, and continue counting as you keep holding your voice. 
* While micro:bit is counting, LED lights will should how strong your voice is, like what we did in the lab this week. 
* Once you stop your voice, micro:bit will show on Display how many seconds you have hold. 
* A new game will start once button A is pressed.

### Instruction

This is a little project that you can include  micro:bit functions that we have learned in the past few weeks - LED, Buttons, Microphone. 

You will reuse the function to map sound level to LED rows. 

You may need the function 
`running_time()` for calculating time difference.

For example: 
```
# when voice is detected, you record the start time: 

start_time = running_time()

# when voice is too low, then you can get how long it has passed: 

time_diff = running_time() - start_time
```
See documents on MicroPython for Micro:bit on the below link: 

https://microbit-micropython.readthedocs.io/en/v1.0.1/microbit.html?highlight=running_time#microbit.running_time

* Send me your solution via email: 
codingsmart101@gmail.com
