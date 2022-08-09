#week-8
<h3> Embedded Programming </h3>
Assignment: Use your programmer (HUZZAH32, ESP32 Feather) to program a circuit with a “led and another component” to do something
Aim: To coded an LED light to turn on and off depending on the basis of potentiometer. This will be programmed with the arduino C++ language, using Arduino IDE, for our ESP32 Feather board.

The arduino code below:
for setting up:
-LED_PIN 11
-POTENTIOMETER_PIN A1
we need to initialize the mode for the pins we want to use:
void setup()
{
  pinMode(11, OUTPUT);
}
we can start to control the brightness of the LED with what we read from the potentiometer:
void loop()
{
  int potentiometerValue = analogRead(A1);
}
Using Arduino map() function which can put a number into a different range.
  int brightness = map(potentiometerValue, 0, 1023, 0, 255);
}

video can be found here - https://drive.google.com/file/d/1hSKlAS_nKLKWMcwf_82Jps-esQRxoBUt/view?usp=sharing
