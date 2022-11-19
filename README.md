
# Jobsheet 1 (GPIO, PWM, ADC) - ESP32

Pada jobsheet 1 terdapat 3 project yaitu simulasi GPIO, PWM, dan ADC menggunakan ESP32.


### Alat dan Bahan

- ESP32
- Arduino IDE (Terinstal ESP32)
- Breadboard
- Kabel Jumper
- Resistor < 220Ω
- LED (5)
- Push Button
- Potensiometer

## Project 1 - GPIO

### Rangkaian

Led menyala saat button ditekan

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

Led menyala dan *blink* saat button ditekan

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)

Led menyala, *blink*, dan berjalan saat button ditekan

![App Screenshot](https://via.placeholder.com/468x300?text=App+Screenshot+Here)
### Coding

1. LED menyala saat button ditekan

```bash
const int buttonPin = 4;
const int ledPin = 5;
int buttonState = 0;

void setup()
const int buttonPin = 4;
const int ledPin = 5;
int buttonState = 0;

void setup()
{
  Serial.begin(115200);
  pinMode(buttonPin, INPUT);
  pinMode(ledPin, OUTPUT);
}

void loop()
{
  buttonState = digitalRead(buttonPin);
  Serial.println(buttonState);
  if (buttonState == HIGH)
  {
    digitalWrite(ledPin, HIGH);
  }
  else
  {
    digitalWrite(ledPin, LOW);
  }
}
```

2. Led menyala dan *blink* saat button ditekan

```bash
const int buttonPin = 4;
const int buttonPin2 = 16;
const int ledPin = 5;
const int ledPin2 = 18;
int buttonState = 0;
int buttonState2 = 0;

void setup() {
  Serial.begin(115200);
  pinMode(buttonPin, INPUT);
  pinMode(buttonPin2, INPUT);
  pinMode(ledPin, OUTPUT);
  pinMode(ledPin2, OUTPUT);
}

void loop() {
  buttonState = digitalRead(buttonPin);
  buttonState2 = digitalRead(buttonPin2);
  Serial.println(buttonState);
  Serial.println(buttonState2);

  if (buttonState == HIGH) {
    digitalWrite(ledPin, HIGH);
  } else {
    digitalWrite(ledPin, LOW);
  }

  if (buttonState2 == HIGH) {
    digitalWrite(ledPin2, HIGH);
    delay(500);
    digitalWrite(ledPin2, LOW);
    delay(500);
  } else {
    digitalWrite(ledPin2, LOW);
  }
}
```

3. Led menyala, *blink*, dan berjalan saat button ditekan

```bash
const int buttonPin = 4;
const int buttonPin2 = 16;
const int buttonPin3 = 17;
const int ledPin = 5;
const int ledPin2 = 18;
const int ledPin3 = 19;
const int ledPin4 = 21;
const int ledPin5 = 3;
int buttonState = 0;
int buttonState2 = 0;
int buttonState3 = 0;

void setup() {
  Serial.begin(115200);
  pinMode(buttonPin, INPUT);
  pinMode(buttonPin2, INPUT);
  pinMode(buttonPin3, INPUT);
  pinMode(ledPin, OUTPUT);
  pinMode(ledPin2, OUTPUT);
  pinMode(ledPin3, OUTPUT);
  pinMode(ledPin4, OUTPUT);
  pinMode(ledPin5, OUTPUT);
}

void loop() {
  buttonState = digitalRead(buttonPin);
  buttonState2 = digitalRead(buttonPin2);
  buttonState3 = digitalRead(buttonPin3);
  Serial.println(buttonState);
  Serial.println(buttonState2);
  Serial.println(buttonState3);

  if (buttonState == HIGH) {
    digitalWrite(ledPin, HIGH);
  } else {
    digitalWrite(ledPin, LOW);
  }

  if (buttonState2 == HIGH) {
    digitalWrite(ledPin2, HIGH);
    delay(500);
    digitalWrite(ledPin2, LOW);
    delay(500);
  } else {
    digitalWrite(ledPin2, LOW);
  }

  if (buttonState3 == HIGH) {
    digitalWrite(ledPin5, LOW);
    digitalWrite(ledPin3, HIGH);
    delay(100);
    digitalWrite(ledPin3, LOW);
    digitalWrite(ledPin4, HIGH);
    delay(100);
    digitalWrite(ledPin4, LOW);
    digitalWrite(ledPin5, HIGH);
    delay(100);
  } else {
    digitalWrite(ledPin3, LOW);
    digitalWrite(ledPin4, LOW);
    digitalWrite(ledPin5, LOW);
  }
}
```
### Hasil

![App Screenshot](https://cdn.discordapp.com/attachments/1023768274737053788/1043461750466560050/GPIO1.gif)

