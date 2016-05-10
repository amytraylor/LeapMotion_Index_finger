# LeapMotion_Index_finger
Adaptation of "LeapMotion_Fingertips_15Inputs" adjusted to only track the index finger plus added velocity.

This code was adapted from Rebecca Fiebrink's "LeapMotion_Fingertips_15Inputs" from her Machine Learning course on Kadenze. Her code is found here: http://www.wekinator.org/examples/#Leap_Motion_hardware_sensor

She adapted her code and added Wekinator functionality from the original library example code here: https://github.com/nok/leap-motion-processing/blob/master/examples/e1_basic/e1_basic.pde

I have altered the code to only send OSC messages for one finger, the index or pointer finger, for the purposes of later using the Leap Motion for projection art pieces that follow the finger in their movement. There is also a new velocity message sent to be used for added movement in the output code.

Further development will include incorporating both direct following of Leap Motion finger position as well as machine learning of gestures.
