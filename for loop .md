# Ardunio-workshop

#define LED 8
void setup() {
  pinMode(LED,OUTPUT);
  // put your setup code here, to run once:

}

void loop() {
  // put your main code here, to run repeatedly:

for(int i=0;i<5; i++){
digitalWrite(LED,HIGH);
delay(1000);
digitalWrite(LED,LOW);
delay(1000);
}
delay(3000);
}
