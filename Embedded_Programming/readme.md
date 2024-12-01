## A glove that emulate the characteristics of a mouse
    1. MPU read roll and pitch to see the direction and velocity of the mouse
    2. Flex sensor tell that users want to drag the mouse or just move the mouse
    3. The data from 2 sensors will be store into a frame and transmitted into PC
    through Bluetooth serial port

## Some lines that developers need to note
    1. Line 64 : declaring variable for sensors, frame and task id for creating tasks
    2. Line 130 : init mpu, adc continuous conversion
    3. Line 159: creating tasks
    4. Line 427: defining action in tasks

## For more information about all components in this project read these file:
    1. MPU_6050.c
    

## Author
    @ Đào Anh Phi
    @ Phạm Dương Quỳnh 

## Code này chẳng có gì để đọc, đứa nào đọc không hiểu chứng tỏ đứa đó ngu. Đọc không hiểu thì thôi, cút mẹ nó đi đừng hỏi hang gì cả