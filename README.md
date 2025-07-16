# Jayden's NFC Business Card

This is my custom electronic business card with an NFC tag for easy contact information sharing.
-


# Figures

**Total Minimum Cost:** $3 USD/card

**Total Hours Spent:** 5 hrs

**Total Days Spent:** 2 days

*See JOURNAL.md and the BOM below for an in-depth explanation of these numbers.*


# How it Works

This NFC business card (or 'hacker card' as it was made through Hack Club's Highway grant program) includes an NFC tag, a resistor, a capacitor, an antenna, and a red 0402 LED. The antenna interacts with the device that reads the NFC, harvests energy from it to activate the chip, sends my contact information back to the reader, and lights up an LED to show that information was transmitted.

PCB
-

This entire NFC business card is made on one assembled PCB board with an appropriate schematic. I was hoping to have the LED on the front of the PCB, where all the aesthetic design is, but due to costs, this may change.

SCHEMATIC

PCB


# The 'Why' Behind the Project

I first knew about hacker cards due to the rise in popularity of them from the Highway hardware grant program run by Hack Club. Because so many people were doing them, and they were so simple, their point reward value was reduced to 1pt. However, this was perfect for me as I've always wanted something like this where I could just tap a card to someone's phone and transmit my contact info, and I had an odd number of points for Highway.


# Bill of Materials (BOM)

| Quantity | Part               | Price Per Part | Notes                                                                                             |
|----------|--------------------|----------------|---------------------------------------------------------------------------------------------------|
| 2        | PCB                | N/A            | 5-pack; price handled by JLCPCB coupon; doubling this (quantity 2) means doubling everything else |
| 10       | 220uF Capacitor    | N/A            | Price too small; negligible                                                                       |
| 10       | NT3H2111W0FHKH NFC | 0.88           |                                                                                                   |
| 10       | Red LED0402        | N/A            | Price too small; negligible                                                                       |
| 10       | 47Ω Resistor0402   | N/A            | Price too small; negligible                                                                       |