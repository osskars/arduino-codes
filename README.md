# arduino-codes
arduino kodi


# arduino-
luksafors
int LED_pin1 =6;
 int LED_pin2 =5;
 int LED_pin3 =4;

void setup()
{
 pinMode(LED_pin1, OUTPUT);
 pinMode(LED_pin2, OUTPUT);
 pinMode(LED_pin3, OUTPUT);
 
}

void loop() 
{
  
  //zaļš
 digitalWrite(6, HIGH);
 delay(1800);
 digitalWrite(6, LOW);
 delay(300);
  //mirgošana
  digitalWrite(6, HIGH);
 delay(300);
 digitalWrite(6, LOW);
 delay(300);
 digitalWrite(6, HIGH);
 delay(300);
 digitalWrite(6, LOW);
 delay(300); 

//dzeltens
 digitalWrite(5, HIGH);
 delay(1800);
 digitalWrite(5, LOW);
 delay(300);
 //mirgošana
  digitalWrite(5, HIGH);
 delay(300);
 digitalWrite(5, LOW);
 delay(300);
  digitalWrite(5, HIGH);
 delay(300);
 digitalWrite(5, LOW);
 delay(300);
 
  
//sarkans
 digitalWrite(4, HIGH);
 delay(1800);

//dzeltens
 digitalWrite(5, HIGH);
 delay(1800);

 //iesledzas zaļš
 digitalWrite(4, LOW);
 digitalWrite(5, LOW);
 delay(50);


}
