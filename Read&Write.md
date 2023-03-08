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
![image](https://user-images.githubusercontent.com/127253124/223730346-fa62a289-da9b-4f2a-bcca-b2b9bbe94454.png)
