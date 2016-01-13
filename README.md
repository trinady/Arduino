# Arduino

// how to program pin 2 on an Uno
// punctuation is key for this programing
// i have found its easiest to find close to what you are trying for and then copy and paste

void setup() {
  // name digital pin 2 as an output.
  pinMode(2, OUTPUT);

void loop() {
  digitalWrite(2, HIGH);   // turns on pin 2 (HIGH is sign for output on )
  delay(1000);              // wait 1000 miliseconds ( 1 second)
  digitalWrite(2, LOW);    // turns off pin 2 ( LOW is sign for output off)
  delay(1000);              // wait for a second
}
