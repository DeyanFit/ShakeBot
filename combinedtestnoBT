#define stepPin 8
#define dirPin 9

int in1 = 2;
int in2 = 4;
int enA = 3;

int in3 = 5;
int in4 = 7;
int enB = 6;

void setup() {

  pinMode(stepPin,OUTPUT); 
  pinMode(dirPin,OUTPUT);
  pinMode(in1, OUTPUT);
  pinMode(in2, OUTPUT);
  pinMode(enA, OUTPUT);
  pinMode(in3, OUTPUT);
  pinMode(in4, OUTPUT);
  pinMode(enB, OUTPUT);
  
}
void loop() {
  
  digitalWrite(in1, HIGH);
  digitalWrite(in2, LOW);
  digitalWrite(in3, HIGH);
  digitalWrite(in4, LOW);
  digitalWrite(enA, 100);
  digitalWrite(enB, 100);
  
  delay(3000);

  digitalWrite(in1, LOW);
  digitalWrite(in2, LOW);
  digitalWrite(in3, LOW);
  digitalWrite(in4, LOW);
  digitalWrite(enA, 100);
  digitalWrite(enB, 100);

  digitalWrite(dirPin,HIGH);
   for(int x = 0; x < 8000; x++) {
    digitalWrite(stepPin,HIGH); 
    delayMicroseconds(1000);    
    digitalWrite(stepPin,LOW); 
    delayMicroseconds(1000); 
  }

}
