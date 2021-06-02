void setup() 
{
 pinMode(13, OUTPUT); 
 Serial.begin(9600);
 }
 void loop()
{
 while(Serial.available())
 {
 int TechTrunk = Serial.read();
 if(TechTrunk=='1')
 {
 digitalWrite(13,LOW); 
 }
 else if((TechTrunk=='2'))
 {
 digitalWrite(13,LOW);
 
 }
 }
 }
