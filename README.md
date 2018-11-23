# robotc-vex-headers
A bunch of crap for VEX IQ on ROBOTC

## functions

### move(int movement, int speed)
Move at the given speed. Possible inputs are:  
LEFT or 0  
RIGHT or 1  
FORWARD or 2  
BACKWARD or 3  

### waitForEncoderValue(int value)
Reset the encoders and wait for a given value.  
Not currently working.  

### waitForButtonPress(int release)
Wait until a button is pressed. If release is equal to 1,  
also wait for the button to be released.
