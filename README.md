# ⭐ Starbie

<img width="1083" height="637" alt="starbie" src="https://github.com/user-attachments/assets/eb8d4d73-d670-446e-b883-03b3cf70e64f" />


## What's a Starbie and why am I making it?

A Starbie is a mix of a starboy and a Tamagotchi. Basically, it's a little digital pet that you can interact with, but instead of living on your phone, it lives on a PCB!

I'm making Starbie as part of Hack Club's Half Life program, where I get to learn how to design and build my own electronic project from scratch :)))

I chose Starbie because it was the Week 1 guide project for total beginners (like me, **DUHH**). I wanted to challenge myself and learn more about electronics, PCB design, and coding.

## How does it work?

Starbie has a few main components that work together to bring it to life:

- **Microcontroller (XIAO ESP32-C3):** The brain of the project! It runs the code that controls how Starbie behaves.
- **OLED screen:** This is where Starbie's face and expressions appear.
- **Buttons:** These let me interact with Starbie and trigger different actions.
- **DHT11 sensor:** Measures temperature and humidity.
- **MPU6050:** A motion sensor that measures movement and orientation.

All these components connect through a custom-designed PCB (printed circuit board), which I designed using KiCad. The firmware tells the microcontroller what to do, including displaying my custom character on the screen.

## Features!

- **Custom jellyfish sprite:** A pixel-art character designed by me to give Starbie its own personality.
- **OLED display:** Shows Starbie's character and expressions.
- **Button interaction:** Two physical buttons provide inputs for interacting with Starbie.
- **Temperature and humidity sensing:** The DHT11 sensor collects environmental readings.
- **Motion sensing:** The MPU6050 detects movement and orientation.
- **Custom star-shaped PCB:** Designed in KiCad to bring the components together.
- **Custom firmware:** Written for the XIAO ESP32-C3 microcontroller to control the display and device behaviour.

## Software and Tools

- **KiCad:** Schematic capture and PCB design.
- **Arduino IDE:** Firmware development.
- **C++:** Programming the microcontroller.
- **Pixel art:** Designing the custom jellyfish sprite.
- **GitHub:** Storing my project files and documentation.

## Design

### PCB

The PCB has a custom star-shaped outline, with decorative details that give it a playful look while keeping the electronics together on one board.

<img width="842" height="714" alt="Screenshot 2026-10-30 7 32 38 PM" src="https://github.com/user-attachments/assets/72b1eeb6-c04d-425a-9ac8-59254181625c" />


### Starbie's Character

Meet my custom jellyfish sprite! I designed it in black and white for the OLED display. I plan to experiment with additional expressions and reactions as I develop the firmware.

<img width="96" height="96" alt="sprite" src="https://github.com/user-attachments/assets/0cd8d144-78ae-4ee6-95cc-de5c08a886ad" />


## Bill of Materials (BOM)

| Part | Qty | Unit Price | Total | Vendor |
|---|---:|---:|---:|---|
| XIAO ESP32-C3 (Main microcontroller) | 1 | $11.61 | $11.61 | [AliExpress](https://www.aliexpress.com/item/1005007378847580.html?mp=1) |
| 0.96-inch I2C OLED Display | 1 | $1.22 | $1.22 | [AliExpress](https://www.aliexpress.com/w/wholesale-0.96-inch-I2C-OLED-display-connector.html) |
| 8-pin Header | 1 | $1.22 | $1.22 | [AliExpress](https://www.aliexpress.com/item/1005012063141186.html) |
| DHT11 Temperature and Humidity Sensor | 1 | $1.22 | $1.22 | [AliExpress](https://www.aliexpress.com/item/1005008953430940.html) |
| Push Button | 1 | $1.22 | $1.22 | [AliExpress](https://www.aliexpress.com/item/1005012448645805.html) |
| 10kΩ Resistor | 1 | $1.22 | $1.22 | [AliExpress](https://www.aliexpress.com/item/1005007539842999.html) |
| MPU6050 Accelerometer and Gyroscope | 1 | $1.22 | $1.22 | [AliExpress](https://www.aliexpress.com/item/1005011826877217.html) |
| Custom PCB | 1 | $11.61 | $11.61 | [JLCPCB](https://cart.jlcpcb.com/shopcart/cart/) |
| **Total** | | | **$26.33** | |


## Final Thoughts & Next Steps

Overall, this has been a really enjoyable project and a good way to test my patience ;) It took me A LOT of time, and my Chromebook kept crashing, but I enjoyed the process.

I learned how to work with KiCad, design a PCB, understand electronic connections, and write firmware for a microcontroller. There were definitely moments when I wanted to give up and restart (and I actually did restart a few times lol), but I learned something new each time.

Thank you to Hack Club and the Half Life community for making this beginner-friendly and giving me the opportunity to try something completely new!

My next step is to get the components, assemble the PCB, and bring Starbie to life.

**Week 1: SUCCESS! ⭐**

## Credits

Built as part of Hack Club's Half Life program. The beginner guide and community helped me get started with my first electronics project.
