## STARBIE

<img width="1083" height="637" alt="starbie" src="https://github.com/user-attachments/assets/3531317b-c431-4101-827d-98e61a3f1403" />

## Whats a starbie and why am I making it

A starbie is a mix of a starboy and tamagotchi. you basically have an online pet that you can interact with it.It basically a little digital pet thats on a PCB instead of your phone!
I'm making Starbie as part of Hack Club's Half Life program, where I get to learn how to design and build my own electronic project from scratch :))). the reason it was the starbie specifically was because it was the week one guide prject for total beginners (like me **DUHH**) I wanted to challenge myself and learn more about electronics, PCB design, and coding.

## How does it work
Starbie has a few main components that work together to bring it to life:

the microcontroller (XIAO ESP32-C3): The brain of the project! It runs the code that controls how Starbie behaves.
the OLED screen: This is where Starbie's face and expressions appear.
the buttons: These let me interact with Starbie and, as I develop the firmware and give it different reactions.
the RGB LED: This adds a little extra colour and personality to the board.

All these components connect through a custom-designed PCB (printed circuit board), which I designed using KiCad. The firmware tells the microcontroller what to do, including displaying my cusom character on the screen.

## features!
-Custom jellyfish sprite: A pixel-art character designed by me to give Starbie its own personality
. 
-OLED display: Shows the character on a small screen. 

-Button interaction: A physical button provides an input for interacting with Starbie. More reactions can be added as the firmware develops.

-RGB LED: Adds colour and a visual indicator to the board. 

-Custom star-shaped PCB: Designed in KiCad to bring all the components together. 

-Custom firmware: Written for the XIAO ESP32-C3 microcontroller to control the display and device behaviour. 
## software and tool
-KiCad: Schematic capture and PCB design

-Arduino IDE: Firmware development

-C++: Programming the microcontroller

-Pixel art: Designing the custom jellyfish sprite

-GitHub: The beginners guide and "storage"

## Design

*PCB*

The PCB has a custom star-shaped outline, with decorative details that give it a playful look while keeping the electronics together on one board.

<img width="1083" height="637" alt="starbie" src="https://github.com/user-attachments/assets/3531317b-c431-4101-827d-98e61a3f1403" />

*Starbies character*

meet my custom jellyfish sprite! I designed it in black and white for the OLED display. I plan to experiment with additional expressions and reactions as I develop the firmware.

<img width="96" height="96" alt="sprite" src="https://github.com/user-attachments/assets/df3a0d3f-131d-41f3-ab54-c95529f38810" />


## Final Thoughts & Next Steps
Overall, this was a really enjoyable project and a good way to test my patience ;) It took me alot of time and my chromebook kept crashing out but I enjoyed it all and thank half-life for making this beginner friendly! I now have to figure out the funding and what to buy and how to make so I stay in the $30 budget (sitting nicely at $28.37 right now!).

## Bill of Materials (BOM)

| Component | Description | Quantity | Unit Cost | Total Cost | Supplier |
|---|---|---:|---:|---:|---|
| PCB | Circuit board | 1 | $5.69 | $5.69 | JLCPCB |
| OLED | Screen | 1 | $0.99 | $0.99 | AliExpress |
| Push button | User control | 1 | $0.99 | $0.99 | AliExpress |
| Headers | Connect the components | 1 | $1.32 | $1.32 | AliExpress |
| XIAO ESP32-C3 | Main microcontroller | 1 | $8.04 | $8.04 | Alibaba |
| RGB LED | Indicates whether the system is working | 1 | $3.90 | $3.90 | Alibaba |
| **Parts subtotal** | — | — | — | **$20.93** | — |
| Tax & shipping | — | — | — | $7.44 | — |
| **Grand total** | — | — | — | **$28.37** | — |

**week 1: SUCCESS!**

## credits
Built as part of Hack Club's Half Life program. The beginner guide and community helped me get started with my first electronics project.
