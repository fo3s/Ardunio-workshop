# Ardunio-workshop
#define LED 8  //set pin 8 for LED 
#define Button 7
int Button_Value; 
void setup() {
    // put your setup code here, to run once:
  pinMode(LED,OUTPUT); 
  pinMode(Button,INPUT);
}

void loop() {
  // put your main code here, to run repeatedly:
 Button_Value= digitalRead(Button);
  
 if(Button_Value == 1){
digitalWrite(LED,HIGH); // turn ON LED
 }
else
digitalWrite(LED,LOW); // turn OFF LED

}
![image](https://user-images.githubusercontent.com/127253124/223732783-497cfb9c-0243-4f4d-93d8-6b9bd23e9d58.png)
