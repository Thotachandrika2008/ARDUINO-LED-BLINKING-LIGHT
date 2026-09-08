# ARDUINO-LED-BLINKING-LIGHT
My first embedded systems project - LED blink simulation using Arduino Uno in Tinkercad

🎯 Aim: To simulate LED blinking using Arduino Uno R3 in Tinkercad Circuits

🔧 Components Used:
- Arduino Uno R3
- Red LED, 220Ω Resistor, Jumper Wires

🔌 Connection:
- Arduino Pin 8 -> Resistor -> LED Anode (Long leg)
- Arduino GND -> LED Cathode (Short leg)

 
### 💻 Code
void setup() {
  pinMode(8, OUTPUT);
}
void loop() {
  digitalWrite(13, HIGH);
  delay(1000);
  digitalWrite(13, LOW);
  delay(1000);
}

✅ Result: LED blinks every 1 second

Learned: Breadboard, LED polarity, Arduino basics, Tinkercad simulation
This is my first project for my Embedded Systems internship portfolio.

🔗 Live Simulation: https://www.tinkercad.com/things/h9v8fdftA3z-arduino-led-blinking-project?sharecode=ojE3LBV2k0zuZiw1408e0DkTDF9NRoR9m1_Nx9upWPw
 


