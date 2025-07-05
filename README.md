# emomacropad
The idea for our hackpad(first project) was emojis.

We LOVE emojis. 😛
What if it wasn't so inconvenient to use emojis on your computer? 😣
What if you had a custom macropad with your top 6 most used emojis! 😨
Oh wait! That doesn't exist. 😭

So we made one. 😺

Sidenote: This uses a unicode package, that could be modified for less silly purposes such as typing accents in other languages.


We started with a kicad schematic:


![image](https://github.com/user-attachments/assets/940bb77f-93d0-4a18-b8ac-076335961e0a)

We used a XIAO-RP2040-DIP microcontroller, 3 LEDS, and 6 keys for our top 6 emojis.

We did the pcb next and decided on a 2 by 3 grid for the keys with the microcontroller on one end for easy USB access.


![image](https://github.com/user-attachments/assets/f3a9b516-d5c3-4579-8dcd-da809c7cbf18)

We finished with a 3d model of the top and bottom:
![WhatsApp Image 2025-06-30 at 15 57 06_42b4655e](https://github.com/user-attachments/assets/9e657471-e328-46d8-aad1-caf781350e71)
![WhatsApp Image 2025-06-30 at 15 57 47_dbb89ba6](https://github.com/user-attachments/assets/b9dc2f8a-e947-432c-af9d-000e2b8da8a8)

![WhatsApp Image 2025-07-04 at 18 36 47_19875069](https://github.com/user-attachments/assets/e6164322-a696-49ad-a775-59e6b8c420ca)

| Item                        | Quantity | Notes                                                                 
|-----------------------------|----------|-----------------------------------------------------------------------
| Seeed XIAO RP2040           | 1        | Microcontroller; comes unsoldered with headers                        
| MX-style switches           | 6        | Mechanical key switches                                               
| 1N4148 diodes (through-hole)| 6        | One per switch for matrix wiring                                     
| Blank DSA keycaps (black)   | 6        | Low-profile uniform keycaps                                          
| SK6812 MINI-E LEDs          | 3        | Per-switch RGB lighting                 
| M3x16mm screws              | 4        | For case assembly                                                     
| 3D printed case             | 1        | Only 3D printing allowed (no acrylic), estimate cost 5$                 

Our posture was notably incredible throughout the whole coding process.
![WhatsApp Image 2025-06-30 at 16 11 49_f42e6659](https://github.com/user-attachments/assets/e12bd7ea-4fa2-4508-a019-a1071df35284)

And that was the end of our first project.
