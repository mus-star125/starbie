ATTEMPT 2 # starbie
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

## Devlogs

### CHALLENGE 1: Downloading KiCad & Figuring out Linux
* **Time Spent:** About 2 hours (which i wasn't able to count in my half life hours)
* **What happened:** Before I even got to the instructions i ran into my first problem: downloading KiCad. Now this step is really easy on windows or mac but unfortunately I don't have those and had to use my chrome book. The process of downloading KiCad on Chromebook is different and was completely new to me. I had to start by installing Linux - which is a tiny computer in my computer- I assigned it about 10GB and had to code- download KiCad using terminal - which is according to google: "a command-line interface application used to run text-based commands, access a Linux development environment, or perform system diagnostics."
* **How I fixed it:** After about an hour of trying to figure the code out i finally got it to install but then i realised 10GB was not enough so I moved it up to 25GB (That work wayy better). For some reason it was a lot more tedious then it should have been. 
* **Lessons learnt:** This wasn't as simple as I thought it would be, but i also learned that Linux was a mini computer system on mine and learned how to operate it :)

**Some pics of me trying to figure linux and terminal out:**
<img width="990" height="723" alt="Screenshot 2026-10-05 7 14 41 PM" src="https://github.com/user-attachments/assets/b9f78645-9ae8-4eae-91ee-bbce091f2b47" />
<img width="1020" height="653" alt="Screenshot 2026-10-05 7 33 18 PM" src="https://github.com/user-attachments/assets/e3068965-ece0-4fed-9661-4f6879a7b671" />
<img width="1020" height="654" alt="Screenshot 2026-10-05 7 37 12 PM" src="https://github.com/user-attachments/assets/f7fa1020-1865-4207-9c23-e369c508f600" />

---

### CHALLENGE 2: Navigating KiCad & The Schematic Editor
* **Time Spent:** About 3.5 hours
* **What happened:** I just could not understand the preferences and after downloading the "week one guide"zip I couldn't figure out how to put it onto KiCad, So my YouTube search started. I looked for videos and videos and ended up turning to slack, this was my last choice because I have a hard time turning for help since i enjoy figuring things out on my own and someone (i cant remember the @) sent a really helpful video which finally helped me understand it. 
* **Another one:** So, i finally opened a schematic file and started searching for all the parts- honestly I'm still figuring out what each part does and how it all works but whatever info i find out Im going to add in here later. I messed up again, I couldn't find the imported parts like the XIAO-ESP32-C3-SMD (which was the BRAIN of this project) at this point I was quite frustrated; whenever something seemed like it was going well another challenge came up... 
* **How I fixed it:** I wasn't a quitter and by some playing around they appeared in my library (Again i had to share these files with Linux and it was making everything more difficult). But looking back at it I enjoy this process, when it all clicks all that frustration and hard work feels worth it! I made my schematic file and I was soo proud of the result! I couldn't believe I designed it all on my own (with the instructions and youtube <3). Finishing the schematic editor took me about 3.5 hours and I was really happy with the result!

**My files and the final schematic layout:**
<img width="3264" height="2448" alt="image0 (4)" src="https://github.com/user-attachments/assets/2c487e8b-8c48-4841-967f-40a1786c7367" />
<img width="3264" height="2448" alt="image0" src="https://github.com/user-attachments/assets/7bc384e3-d3f5-47e7-a830-961f6a418860" />

---

### CHALLENGE 3: Making the PCB (Not as challenging as the Schematic :D)
* **Time Spent:** About 6.5 hours in total
* **What happened:** I was really excited seeing my schematic becoming a model! It was kind of intimidating with the hundreds of tools in the PCB editor, but it ended up working out. I started by organising my parts like the guide, i then went on the edge cut layer to make the star outline, this was probably the easiest part out of the project :) then i connected the wires. 
* **what I did:** I was kind of worried because i did not have the same wiring as the guide, but with some research i realised that it will work the same. Then I added funny text and cute pictures on the board (Like the cute balloon dog). In all, the PCB was a much more enjoyable process than the schematic, but it still took me some time to get it done.
* **Fixing the star shape:** Then it occured to me that i wasn't a big fan of my star shape so I had to go back into the PCB editor to fix it, which was tedious because i had to re-download and re-upload my gerber files onto github and JLCPCB. I finally downloaded the Gerber files and uploaded them onto my github.

**Here is how the board turned out:**
 <img width="2448" height="3264" alt="image1 (3)" src="https://github.com/user-attachments/assets/9ece72d0-c7f2-4e3b-8aa8-39b136ea499d" />



---

### CHALLENGE 4: Writing The Firmware & Sprite Design
* **Time Spent:** About 2 hours
* **What happened:** The firmware was the quickest and easiest process out of the whole project; i used the beginner guide and made my own character. 
* **How I handled it:** Making my sprite was difficult since i could only use black and white but I'm really proud with how it turned out. I have some things in mind that i want to experiment with but am waiting for the hardware for that.

**Here is my custom Jellyfish Sprite:**
<img width="96" height="96" alt="sprite" src="https://github.com/user-attachments/assets/df3a0d3f-131d-41f3-ab54-c95529f38810" />

---

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

## More pic
