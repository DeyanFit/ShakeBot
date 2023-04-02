#define stepPin 8
#define dirPin 9
 
void setup() {
  pinMode(stepPin,OUTPUT); 
  pinMode(dirPin,OUTPUT);
}
void loop() {
  digitalWrite(dirPin,HIGH); //R->L
    for(int x = 0; x < 800; x++) {
    digitalWrite(stepPin,HIGH); 
    delayMicroseconds(700);    
    digitalWrite(stepPin,LOW); 
    delayMicroseconds(700); 
  }
  delay(1000);
  
  digitalWrite(dirPin,LOW); //L->R
  for(int x = 0; x < 1600; x++) {
    digitalWrite(stepPin,HIGH);
    delayMicroseconds(500);
    digitalWrite(stepPin,LOW);
    delayMicroseconds(500);
  }
  delay(1000);
}
