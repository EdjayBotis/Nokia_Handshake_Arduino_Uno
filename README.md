# Nokia Handshake Arduino Project

This project recreates the iconic Nokia startup handshake and tone using an **Arduino Uno**, an **OLED SSD1306 display**, and a **buzzer**.

## Components Used

- Arduino Uno  
- OLED SSD1306 (I2C)  
- Passive Buzzer  
- Jumper Wires  
- Breadboard or Soldered Setup  

## Pin Connections

| Component | Arduino Pin |
|----------|-------------|
| OLED SDA | A4          |
| OLED SCL | A5          |
| Buzzer   | D11         |
| VCC      | 5V          |
| GND      | GND         |

## Libraries Required

Make sure you have these libraries installed in the Arduino IDE:

- `Adafruit_GFX`
- `Adafruit_SSD1306`
- `Wire`

You can install them via **Library Manager** in the Arduino IDE.

## Nokia Tune Credit

The Nokia startup tune used in this project was sourced from a **GitHub user** (credit to the original creator — i forgot the name of the github user).

## How It Works

1. The OLED displays a short animation mimicking the classic Nokia handshake logo.
2. The buzzer plays the nostalgic Nokia startup tone.
3. It’s all timed and synced using Arduino code for a satisfying retro experience.

## License

This project is made for educational purposes and personal satisfaction. Nokia, its logo, and startup sound are properties of Nokia Corporation.


## 
Created by Edjay

Feel free to fork, modify, or improve this project!
