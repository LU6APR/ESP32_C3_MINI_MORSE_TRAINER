# ESP32_C3_MINI_MORSE_TRAINER
ESP32 C3 MINI MORSE TRAINER / OSCILLATOR FOR IAMBIC KEYS

Iambic Keyer + CW Decoder with ESP32-C3 Mini
 Author: LU6APR Pablo Ramos.
________________________________________
1. PROJECT DESCRIPTION
This project consists of building an electronic Iambic Keyer with an integrated Morse code decoder, based on the ESP32-C3 Super Mini microcontroller.
The device allows:
•	Transmitting Morse code using an iambic paddle (two levers: dot and dash)
•	Automatically decoding the transmitted Morse code
•	Displaying the decoded text on an OLED screen (4 lines)
•	Adjusting the transmission speed (WPM)
•	Automatic spacing after 1 second of pause
•	Automatic screen clearing when 4 lines are completed
•	Manual clearing with a short button press

<img width="1971" height="1354" alt="circuit_image" src="https://github.com/user-attachments/assets/04f94726-7019-4d6b-8713-7bc5f921db1e" />

Copy the code into the Arduino IDE, select the port and the ESP32 C3 mini (in my case I used the LOLIN C3 MINI), compile and upload it to the ESP32 C3 mini.

Note: the project can be assembled without the display, and it will still work as an oscillator for iambic keys...

14/8/2026

<strong>LU5DZY</strong> shared a circuit with an optocoupler to the TX, following a recommendation in a CW group of colleagues/friends.
The circuit is below. Thanks Nico!

<img width="1971" height="1354" alt="circuit_image" src="nico_opto.png" />

Video: [LU5DZY_Opto.mp4](LU5DZY_Opto.mp4)

29/9/2026

<strong>PY3DU</strong>, Improved speed selection: now you can adjust it either by pressing the button or using the paddles (dits and dahs) to increase or decrease the speed. Thanks, Luiz! PY3DU.
Available in  releases...

Video: [PY3DU_SPEED_CHANGE.mp4](PY3DU_spd_chng.mp4)

30/9/2026

<strong>LU6APR</strong> The video library has been updated with the improvement in speed selection, allowing adjustment by pressing the button or using the paddles to increase or decrease the speed, as proposed by PY3DU. Available in the releases section...
