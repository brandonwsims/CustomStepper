# CustomStepper
Custom stepper motor code for a laser harp.

HL  HR  LL  LR
1   0   0   1   Moves Clockwise
0   1   1   0   Move Counter Clockwise
1   1   0   0   Brakes
0   0   1   1   Brakes

Other permutations have undefined or unwanted results.

Clockwise

|     |
|     /
|-(M)-|
/     |
|     |

Counter Clockwise

|     |
/     |
|-(M)-|
|     /
|     |

Brakes

|     |
|     |
|-(M)-|
/     /
|     |

Clockwise

|     |
/     /
|-(M)-|
|     |
|     |
