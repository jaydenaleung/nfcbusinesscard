---
title: "Jayden's NFC Business Card"
author: "Jayden Leung (Hack Club Slack: loliipoppi)"
description: "Electronic business card with NFC tag for easy contact information sharing."
created_at: "2025-07-11"
---

# Time Spent
- **Total hours: 9h**

# July 11th: PCB Design

The day before Undercity, I decided to prime my PCB design skills (that was my role on our team) by building a fun little hacker card (I also had an odd point value, so this would be helpful). I had heard of them through their increasing popularity on the slack, but I didn't know much about them. Turns out, the electronic NFC contact card was a really cool idea that I had been thinking of for weeks, and here was my opportunity to build one.

I found this helpful tutorial on how to do it: https://jams.hackclub.com/jam/hacker-card

It initially took me a long time to research and make the PCB since I wanted to do it in KiCad instead of EasyEDA, which the tutorial used. Eventually, after an hour of frustratingly trying to find the right parts and wiring for other NFC tags, I settled instead for doing what the article recommended.

The silkscreen design was, of course, my favorite part. I really enjoyed the aesthetic design part and wanted it to look as polished as possible. See below!

<img width="464" height="412" alt="Screenshot 2025-07-16 031232" src="https://github.com/user-attachments/assets/0e204048-efb6-4098-ac60-db606c43d5c3" />
<img width="780" height="487" alt="Screenshot 2025-07-16 031227" src="https://github.com/user-attachments/assets/093c9186-c466-4c49-8a5d-71a8d2cdeca1" />

**Total time spent: 3h**


# July 15th: Ordering, BOM, etc.

I finished my project after Undercity by generating the gerber files and wrapping up some details on the PCB design. I made my BOM, journal (here!), and readme, and I also decided to create a JLCPCB order (not ordering it yet) just to see what the price would be. I knew I wanted PCBA since I wanted a lot of cards without having to assemble the small pieces myself. However, PCBA was being really difficult today and messed up my quantity of parts, which ended up giving me a $70 price tag. I knew there was probably no way it could cost that much, but it was also 4AM and I decided to leave it for another day, after I got the project approved.

<img width="773" height="1003" alt="Screenshot 2025-07-16 035410" src="https://github.com/user-attachments/assets/065a5868-1843-4245-82f1-23fffe70439d" />
<img width="2148" height="675" alt="Screenshot 2025-07-16 040807" src="https://github.com/user-attachments/assets/dbb316b8-3047-44b6-9cfd-a2051e3b9d52" />

Why is JLCPCB randomly making only some of my parts 4x quantity...

Final product images:
<img width="1153" height="805" alt="Screenshot 2025-07-16 031257" src="https://github.com/user-attachments/assets/54a7fedb-91e5-4154-885c-08130e51e820" />
<img width="1080" height="688" alt="Screenshot 2025-07-16 031243" src="https://github.com/user-attachments/assets/8b743b44-51c2-48e4-9bc8-4488850bc6a0" />


**Total time spent: 2h**


# July 17th: Another Shot at PCBA

After talking to a few people on Slack, I realized I could significantly reduce the cost of my PCB by using economic PCBA for only assembling one side. Thus, I moved my LED to the back side. I reuploaded the new gerbers, BOM, and CPL, and chose LeadFree HASL for long-term safety and health. I didn't need the solderability from leaded HASL, as I assumed PCBA would solder it perfectly for me anyway. This time, the new cost from economic PCBA and lead-free HASL came about to be about $26 for 5 assembled PCBs, meaning about $5 per card.

**Total time spent: 1h**


# July 17th: Firmware

After placing an order for the PCB, I realized I hadn't written the firmware yet. There is no official code file to flash to NFC tags, but I used the NFC Tools app to write data to it. See https://jams.hackclub.com/jam/hacker-card for more instructions on doing so. I wrote the instructions in a FIRMWARE.md file.

I uploaded a vCard to the NFC with all of my contact information using https://www.vcard.link. Then, I downloaded the .vcf file and hosted it on my personal Vercel website (which I also set up and learned how to use while I was making my vCard!). The link to it can be found here: https://jayden-leung.vercel.app/jaydenleung-contact.vcf. On iPhones, recieving this link through an NFC tag will automatically allow my contact card to pop up. It was really cool!

**Total time spent: 1h**


# July 25th: Custom Artwork

My submission got declined in #highway-pitstop on the Hack Club Slack since it didn't have custom artwork. Although I didn't know that was a requirement for hacker cards, it was a good experience to learn how to adapt to these types of situations as I'd never been rejected before. Nevertheless, I had some fun drawing up my projects on my Kindle Scribe then sending them to import into EasyEDA and onto the silkscreen of the PCB. I made all the artwork on the back of the PCB, and the 'holo' logo on the front is made using Canva too!! Holo is a future company I hope to begin. Hopefully this hacker card will come in handy then with networking! See below for pictures:

<img width="1357" height="978" alt="Screenshot 2025-07-25 at 11 16 45 PM" src="https://github.com/user-attachments/assets/1ca439f5-4546-4322-bc44-04f5b785dcbb" />
<img width="1311" height="1008" alt="Screenshot 2025-07-25 at 11 16 51 PM" src="https://github.com/user-attachments/assets/ded09648-8a72-40b8-bbc6-423ef18d1c67" />
<img width="1500" height="1500" alt="nfcbusinesscard holo full logo" src="https://github.com/user-attachments/assets/049a7e02-67e7-45d7-b3f5-e3f683e820c4" />
<img width="1500" height="1500" alt="astrotrackerh1" src="https://github.com/user-attachments/assets/c3157237-7158-46ca-8a17-3a84fed50229" />
<img width="1500" height="1500" alt="portcullis" src="https://github.com/user-attachments/assets/7794d04a-d498-4c29-9ac9-070b4e2868bd" />
<img width="500" height="500" alt="holo" src="https://github.com/user-attachments/assets/883377bb-f393-446c-bcbb-8e2d9d4b7219" />


**Total time spent: 2h**
