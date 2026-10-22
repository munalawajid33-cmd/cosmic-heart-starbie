# cosmic-heart-starbie
Heart shaped starbie





A heart-shaped, USB-powered desk pet. Shake it and the cat answers you.

Board:
<img width="736" height="495" alt="image" src="https://github.com/user-attachments/assets/6e617897-9e6a-4c6f-bf3d-a2e1e48d8711" />
<img width="692" height="489" alt="image" src="https://github.com/user-attachments/assets/872d84a7-c49d-4a8e-bcc8-1608127c0535" />


Custom pixel-heart board outline (the guide uses a different shape)
Hand-drawn silkscreen art on the front and back: a cat with headphones, music notes, hearts, sparkles, a "Shake Me!" speech bubble and my name
Layout redone so the buttons are mirrored in the two lobes of the heart, with the OLED at the bottom


Firmware (my own additions to Starbie.ino)

Cat Oracle: shake the board and the cat shows a message I wrote (purrfect, ask again, not today, ...) in a box at the top of the screen for 3 seconds
Temperature mood: uses the DHT11. The cat shows a sweat drop and "hot!" above 30 C, and "brr" below 18 C
Startup screen: shows my name and a twinkling star animation when it turns on
Screen saver: the screen dims after 30 seconds of no activity and turns off after 2 minutes. A button press or a shake wakes it
Sparkle trail: a blinking star behind the cat as it walks
My own sprites: a 32x32 cat I drew, plus a second sleepy version that shows during NAP
Renamed menu items (SNACK, PURR) to fit my cat
