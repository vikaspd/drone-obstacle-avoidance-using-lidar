# drone-obstacle-avoidance-using-lidar
This is a simple arduino code to detect the ground distance and hover the drone at a set distance from the ground with a simple flip switch. And also not allowing the throttle input to be executed if the drone's distance is less than the set threshold limit.

Ive used a TF mini as the distance sensor to calculate the ground distance from the drone, arduino nano/arduino UNO , and a small led to show the distance from the drone to the ground by mapping the intensity with the distance.

This code only works with PWM inputs. I've started working on another project where I'll be using sbus signals instead of PWM.
For details on the wiring please refer to the code's comments.
