---
testspace:
---

# Startup 
This test different startup stages of the application, eventually transitioning to the `idle` state. 

The requirements can be found in [state machine](https://github.com/newco/open-project/issues/27).

## Check Transitions
The display will be changed based on the following configurations: 

Mode 1.a | Mode 2.c
-------- | --------
 State 1 | State n

- Check for the first transition after power-up
- Check next step for **id=17.xx**. Should display the local URL. 

Now review the states based on following diagram:

![states](./states.png "State machine")

## Power Scenario
The power scenario requires quick cycling, going over each scene in less than `10` seconds.

- Going online **without** system configuration set to `ABC`
- Verify system turns on and display *blinking every 3 seconds*

## Switch On
The switch-on will be very rapid based on the `Mode 2.c`. 

## Turn off delay

## Full Idle Mode


## Exploratory
Capture observations based on state transitions. Include screenshots with comments.

