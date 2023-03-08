
#include <Servo.h> // Servo Motor Library 

Servo ServoMotor;  // (initialization)create servo object to control a servo 
int pos = 0;    // variable to store the servo position 

void setup() {
 ServoMotor.attach(9);  // attaches the servo on pin 9 to the servo object
}

void loop() {
  for (pos = 0; pos <= 180; pos += 1) { // goes from 0 degrees to 180 degrees 
    // in steps of 1 degree 
    ServoMotor.write(pos);              // tell servo to go to position in variable 'pos'
    delay(15);                       // waits 15ms for the servo to reach the position
  }
  
}

![image](https://user-images.githubusercontent.com/127253124/223697273-1506e06e-e60e-43f3-861f-c521a987fea3.png)

