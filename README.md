# Jayden's NFC Business Card

This is my custom electronic business card with an NFC tag for easy contact information sharing. With a sleek design, the card makes networking and contact info sharing much easier.
-

<img height="450" alt="Screenshot 2025-07-16 031243" src="https://github.com/user-attachments/assets/e1a09740-0ec3-4847-88c8-2a3102d26e5f" />
<img height="450" alt="Screenshot 2025-07-16 031257" src="https://github.com/user-attachments/assets/49d6e19b-876e-4b44-b701-7d055f86a698" />
<img height="450" alt="Screenshot 2025-07-16 031305" src="https://github.com/user-attachments/assets/2772f20e-8c39-48d5-a1c0-28bcd1b076ca" />


# Figures

**Total Minimum Cost:** ~$5 USD/card

**Total Hours Spent:** 9 hrs

**Total Days Spent:** 4 days

*See JOURNAL.md and the BOM below for an in-depth explanation of these numbers.*


# How it Works

This NFC business card (or 'hacker card' as it was made through Hack Club's Highway grant program) includes an NFC tag, a resistor, a capacitor, an antenna, and a red 0402 LED. The antenna interacts with the device that reads the NFC, harvests energy from it to activate the chip, sends my contact information back to the reader, and lights up an LED to show that information was transmitted.

PCB
-

This entire NFC business card is made on one assembled PCB board with an appropriate schematic. I was hoping to have the LED on the front of the PCB, where all the aesthetic design is, but due to costs, it's just on the back now.

The entire back is my custom art!! So is the 'holo' logo on the front. Holo is an upcoming company I hope to launch, and this card will be useful for quick networking.

<img width="464" height="412" alt="Screenshot 2025-07-16 031232" src="https://github.com/user-attachments/assets/2e6c465c-5053-47ed-8a8f-5f8b4bd4cf4d" />

<img width="780" height="487" alt="Screenshot 2025-07-16 031227" src="https://github.com/user-attachments/assets/35453428-ca4f-4009-abbb-9e9953806418" />


# The 'Why' Behind the Project

I first knew about hacker cards due to the rise in popularity of them from the Highway hardware grant program run by Hack Club. Because so many people were doing them, and they were so simple, their point reward value was reduced to 1pt. However, this was perfect for me as I've always wanted something like this where I could just tap a card to someone's phone and transmit my contact info, and I had an odd number of points for Highway.


# Bill of Materials (BOM)

| Quantity | Part               | Price Per Part | Notes                                                                        | Link                                                                                                                                          |
|----------|--------------------|----------------|------------------------------------------------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------|
| 1        | PCB                | $24.25         | 5-pack; price handled by JLCPCB coupon. ~$1 per PCB and ~$4 per PCB assembly | See EasyEDA PCB file.                                                                                                                         |
| 5        | 220uF Capacitor    | N/A            | Price too small; negligible                                                  | https://lcsc.com/product-detail/Multilayer-Ceramic-Capacitors-MLCC-SMD-SMT_Samsung-Electro-Mechanics-CL10B224KA8NNNC_C21120.html?s_z=n_C21120 |
| 5        | NT3H2111W0FHKH NFC | 0.88           |                                                                              | https://lcsc.com/product-detail/RFID-ICs_NXP-NT3H2111W0FHKH_C710403.html?s_z=n_C710403                                                        |
| 5        | Red LED0402        | N/A            | Price too small; negligible                                                  | https://lcsc.com/product-detail/LED-Indication-Discrete_EVERLIGHT-16-213SDRC-S530-A3-TR8_C71911.html?s_z=n_C71911                             |
| 5        | 47Ω Resistor0402   | N/A            | Price too small; negligible                                                  | https://lcsc.com/product-detail/Chip-Resistor-Surface-Mount_UNI-ROYAL-0603WAF470JT5E_C23182.html?s_z=n_C23182                                 |
| Subtotal | $24.25             |                |                                                                              |                                                                                                                                               |
| Shipping & Fees | $11.23              |                |                                                                              |                                                                                                                                               |
| Total    | $35.48             |                |                                                                              |                                                                                                                                               |
