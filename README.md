# PCB Business Card

![Business Card Front](Photos/front.jpeg)



A PCB card, designed as a business card. This PCB contain a logic gate circuit that display my phone number on a 7 segment LEDs

---
![GIF](Photos/demonstration_gif.gif)

---
##  Features
- PCB size: **90 mm × 50 mm**   
- Power: **CR2032 coin cell**  
- Components:
  - `74HC08` — AND gates  
  - `74HC32` — OR gates  
  - `74HC74` — D flip-flops  
  - `NE555` — 1 Hz clock generator  
  - 7-segment-style LED arrangement to visualize digits  
- Integrated **QR code** with my contact information  

---

##  How It Works
- The **NE555 timer** generates a ~1 Hz clock signal.  
- The clock drives the **4-bit counter (made of 4 DFFs)**, which increments automatically.
- Combinational logic (using logic gates) manipulate the counter output to show my phone number.
- The output is displayed using discrete LEDs arranged as digits.  

---
feel free to use, modify, and build your own logic business card.
---

##  About
Created by **Michael Eldin**  
System Validation Engineer  
📧 michaeldin770@gmail.com  
🔗 [LinkedIn](https://www.linkedin.com/in/michael-eldin-37a20b162/)
