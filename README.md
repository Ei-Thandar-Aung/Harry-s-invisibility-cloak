Harry's invisibility cloak

Requirements 
You must need following libraries:

opencv
numpy
time

Why change BGR2HSV?
Opencv default read is BGR format.

Why capture background image using for loop?
If background is stati we can do with single capture. So to capture multiple images of static background, using for loop.

Why capture backgrouond

Step1. Capture and store the background frame.
Step2. Detect the red colored cloth using color detection algorithm.You can change other color rather than using red cloth.
Step3. Segment out the red colored cloth by generating a mask.
Step4. Generate the final augmented output to create the magical effect.
