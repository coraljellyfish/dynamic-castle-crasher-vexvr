# VEX VR Dynamic Castle Crasher Code

What this code does: In a simulation, the robot drives around the platform, crashing all of the virtual "castles" (made out of virtual "building blocks) and clearing the platform of all blocks by pushing them toward the edge and making them fall over. (The platform is a white square with a thick red border.)


Limitations (during the process): Because it is "dynamic," the layout of the "castles" changes every time the code is run. Therefore, it would have been impossible to only plug in hard-coded values (e.g. how many degrees right/left to turn, how many millimeters to drive forward, etc.). However, regardless of the layout of the castles, the robot is able to crash each one of them and clear their building blocks off.

Also, there is no "wall" around the platform that keeps the robot from falling over, so some code was needed to make sure the robot stayed on the platform.


Types of sensors used:
Eye sensor: If the color red was detected, the robot would have to back away a bit to make sure it didn't fall over. (However, it goes a little bit forward first to make any blocks on the border fall over the platform.) Distance sensor: This allowed the robot to sense if there was an object near by to clear off. This enabled the robot to actively hunt for objects. Bumper sensor: The usage of this sensor basically made it so that once the robot found an object and was pushing it (by driving), it wouldn't abandon it after a few seconds. This speeded up the process greatly.

