#define LED_GREEN 8
#define LED_YELLOW 7
#define LED_RED 6

void light_cycle();

void setup() {
  pinMode(LED_RED, OUTPUT);
  pinMode(LED_GREEN, OUTPUT);
  pinMode(LED_YELLOW, OUTPUT);
}

void loop() {
  light_cycle();
}

void light_cycle(){
  digitalWrite(LED_GREEN, HIGH);
  digitalWrite(LED_YELLOW, LOW);
  digitalWrite(LED_RED, LOW);
  delay(2000);

  digitalWrite(LED_GREEN, LOW);
  digitalWrite(LED_YELLOW, HIGH);
  digitalWrite(LED_RED, LOW);
  delay(2000);

  digitalWrite(LED_GREEN, LOW);
  digitalWrite(LED_YELLOW, LOW);
  digitalWrite(LED_RED, HIGH);
  delay(2000);
}
