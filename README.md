# Semaforo
Primer proyecto Bruno
// C++ code

//semaforo vehícular

int LED1 = 11;//verde
int LED2 = 12;//amarillo
int LED3 = 13;//rojo

//semáforo peatonal
int LED4 = 10;//rojo
int LED5 = 9;//verde
  
void setup()
{
  pinMode(LED1, OUTPUT);
  pinMode(LED2, OUTPUT);
  pinMode(LED3, OUTPUT);
  pinMode(LED4, OUTPUT);
  pinMode(LED5, OUTPUT);
}

void loop()
{
  
  digitalWrite(LED4,HIGH);
  delay(800); // Wait for 1000 millisecond(s)
  digitalWrite(LED1,HIGH);
  delay(2000); // Wait for 1000 millisecond(s)
  digitalWrite(LED1, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED1,HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED1, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED1,HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED1, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED2, HIGH);
  delay(1000); // Wait for 1000 millisecond(s)
  digitalWrite(LED2, LOW);
  delay(700); // Wait for 1000 millisecond(s)
  digitalWrite(LED3, HIGH);
  delay(100); // Wait for 1000 millisecond(s)
  digitalWrite(LED4, LOW);
  delay(500); // Wait for 1000 millisecond(s)
  digitalWrite(LED5, HIGH);
  delay(3000); // Wait for 1000 millisecond(s)
  digitalWrite(LED5, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED5,HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED5, LOW);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED5,HIGH);
  delay(300); // Wait for 1000 millisecond(s)
  digitalWrite(LED5, LOW);
  delay(50); // Wait for 1000 millisecond(s)
  digitalWrite(LED3, LOW);
  delay(300); // Wait for 1000 millisecond(s)

  
  

}
