# cosmic-heart-starbie
Heart shaped starbie





A heart-shaped, USB-powered desk pet. Shake it and the cat answers you.

Board:
<img width="736" height="495" alt="image" src="https://github.com/user-attachments/assets/6e617897-9e6a-4c6f-bf3d-a2e1e48d8711" />
<img width="692" height="489" alt="image" src="https://github.com/user-attachments/assets/872d84a7-c49d-4a8e-bcc8-1608127c0535" />


Custom pixel-heart board outline (the guide uses a different shape)
Hand-drawn silkscreen art on the front and back: a cat with headphones, music notes, hearts, sparkles, a "Shake Me!" speech bubble and the name of the pet. my initials at the back are also included.
Layout redone so the buttons are mirrored in the two lobes of the heart, with the OLED at the bottom


Firmware (my own additions to Starbie.ino)

Cat Oracle: shake the board and the cat shows a message I wrote (purrfect, ask again, not today, ...) in a box at the top of the screen for 3 seconds
Temperature mood: uses the DHT11. The cat shows a sweat drop and "hot!" above 30 C, and "brr" below 18 C
Startup screen: shows my name and a twinkling star animation when it turns on
Screen saver: the screen dims after 30 seconds of no activity and turns off after 2 minutes. A button press or a shake wakes it
Sparkle trail: a blinking star behind the cat as it walks
My own sprites: a 32x32 cat I drew, plus a second sleepy version that shows during NAP
Renamed menu items (SNACK, PURR) to fit my cat

 Bill of Materials (BOM)

| Item | Qty | cost(BHD)| cost(dollars) | Source / Link |
| :--- | :--- | :---: | :---: | :--- |
| XIAO ESP32 C3 | 1 | 1.51 | $4 | https://www.temu.com/qa/goods.html?refer_share_id=75fc9b92-c4bb-438e-af53-1483c8a7&_bg_fs=1&goods_id=601099588295925&from_share=1&refer_share_channel=whatsapp_chat&_oak_page_source=417&_oak_region=16&refer_share_suin=RSSBDGQRZLB2XEHSOBQGA35DNQXU2SGXO3D6TZDVIGPLXNBRJ6W2HCNEDKNZMYYIOGHOC4UGNA&share_img=https%3A%2F%2Fimg-eu.kwcdn.com%2Fgoods-detail-img%2F35b7c2%2FyeUWmfsNGd%2F8f20f728a0fc4ab6bb9a5c6c68abbfc8.png&share_ui_type=1&_x_share_id=75fc9b92-c4bb-438e-af53-1483c8a7&refer_page_name=goods&refer_page_id=10032_1791736951229_8uj6zypgti&refer_page_sn=10032&_x_sessn_id=m8wxwrjlei |
| 0.96 OLED | 1 | 2.42 | $6.41 | https://share.temu.com/fo2B2snlRnB |
| MPU6050 | 1 | 4.95 | $13.12 | https://share.temu.com/gicZKMNHfUB |
| DHT11 | 1 | 3.19 | $8.19 | https://share.temu.com/oQAE6SqBJ5B |
| MX Switches | 2 | 3.95 | $10.47 | https://share.temu.com/Yso3pKZKMwB |
| Keycaps | 2 | 1.4 | $3.71 | https://share.temu.com/tN0pxzwWMbB |
| 10k resistor | 1 | 1.69 | $4.48 | https://share.temu.com/93UU8f7UntB |
| PCB | 1 | 3 | $7.95 | https://share.temu.com/TSFyHHeBl1B |



