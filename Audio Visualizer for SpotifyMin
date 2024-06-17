int soundsensor = A0;

int led1 = 2;
int led2 = 3;
int led3 = 4;
int led4 = 5;
int led5 = 6;
int ledu = 7;
int led6 = 8;
int led7 = 9;
int led8 = 10;
int led9 = 11;
int led10 = 12;
int led11 = 13;
float t = 25;
float t1 = 5;
void setup() {
  // put your setup code here, to run once:
pinMode(soundsensor, INPUT);
pinMode(led1,OUTPUT);
pinMode(led2,OUTPUT);
pinMode(led3,OUTPUT);
pinMode(led4,OUTPUT);
pinMode(led5,OUTPUT);
pinMode(ledu,OUTPUT);
pinMode(led6,OUTPUT);
pinMode(led7,OUTPUT);
pinMode(led8,OUTPUT);
pinMode(led9,OUTPUT);
pinMode(led10,OUTPUT);
pinMode(led11,OUTPUT);
Serial.begin(9600);
}

void loop() {
  // put your main code here, to run repeatedly:
int sensorValk= analogRead(soundsensor);
int sensorVal= map(sensorValk, 0, 720, 0, 100);
Serial.println(sensorVal);


if(sensorVal<60){
  digitalWrite(led1,HIGH);
  digitalWrite(led11,HIGH);
  delay(t);}
else{
digitalWrite(led11,LOW);
digitalWrite(led1,LOW);
delay(t1);
}

if(sensorVal<50){
  digitalWrite(led2,HIGH);
  digitalWrite(led10,HIGH);
  delay(t);}
else{
digitalWrite(led10,LOW);
digitalWrite(led2,LOW);
delay(t1);
}

if(sensorVal<40){
  digitalWrite(led3,HIGH);
  digitalWrite(led9,HIGH);
  delay(t);}
else{
digitalWrite(led9,LOW);
digitalWrite(led3,LOW);
delay(t1);
}

if(sensorVal<30){
  digitalWrite(led4,HIGH);
  digitalWrite(led8,HIGH);
  delay(t);}
else{
digitalWrite(led8,LOW);
digitalWrite(led4,LOW);
delay(t1);
}

if(sensorVal<20){
  digitalWrite(led5,HIGH);
  digitalWrite(led7,HIGH);
  delay(t);}
else{
digitalWrite(led7,LOW);
digitalWrite(led5,LOW);
delay(t1);
}

if(sensorVal<5){
  digitalWrite(led6,HIGH);
  digitalWrite(ledu,HIGH);
  delay(t);}
else{
digitalWrite(led6,LOW);
digitalWrite(ledu,LOW);
  delay(t1);
}










}
