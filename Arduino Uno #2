#define LED1 A0
#define BOT2 6

void setup()
{
  pinMode(LED1, OUTPUT);
  pinMode(BOT2, INPUT_PULLUP);
  Serial.begin(9600);
}

void loop()
{
  if (Serial.available())
  { char dados = Serial.read();
   digitalWrite(LED1,dados);
   
  Serial.write(!digitalRead(BOT2));
  delay(500);
  }
}
