*Note: This firmware uses the NFC Tools app on iOS by wakdev. Follow the instructions below to flash data to the NFC tag as there is no real "code" involved.*


TO FLASH DATA ONTO NFC:

Go to the home page of the app.

Click "Other".

Click "Advanced NFC commands".

Click "I understand".

Click the text box next to "Data :", then paste "A2:03:E1:10:6D:00,A2:04:03:04:D8:00,A2:05:00:00:FE:00" into the text box. // This formats the chip and unlocks it for writing. BE VERY CAREFUL TO PASTE EXACTLY THIS LINE OR YOU RISK FRYING THE CHIP.

Click "Send command".

Hold your phone against the NFC chip and wait for it to write to it.

Return to the home page.

Click "Write".

Click "Add a record".

Click "URL / URI".

Click the text box, then paste "jayden-leung.vercel.app/jaydenleung-contact.vcf" into it.

Click "Write".

Hold your phone against the NFC chip and wait for it to write to it.


TO READ NFC DATA:

If you are using an iPhone XS or XR and you have iOS 14+: Place the phone near the NFC tag and a notification will pop up.

If you are using an older iPhone model or an older iOS version: Go to the home page of the NFC Tools app, click "Read", and place the phone near the NFC tag.