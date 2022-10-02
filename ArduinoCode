float Voltage;
void battery_voltage(void) {
  Voltage=(float)analogRead(15)/62;
}
void setup() {
  Serial.begin(57600);
  pinMode(13, OUTPUT);
  digitalWrite(13, HIGH);
}
void loop() {
  battery_voltage();
  Serial.print(Voltage);
  Serial.println("V");
  delay(50);
}
