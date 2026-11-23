# Root Reflex (Reflex Riot)

## 1. About the Project

Root Reflex is a reaction game we made using an Arduino Mega, different sensors, and Java. The player has to complete different actions as quickly as possible.

The Arduino reads the sensors and detects the player's actions, while Java runs the game and shows the results on the computer.

## 2. Components Used

- Arduino Mega 2560
- MPU-6050 Gyroscope
- Ultrasonic Sensor
- Microphone Sensor
- Rotary Encoder
- RFID Reader
- Light Sensor
- RGB LED
- Push Buttons
- XBee Modules

## 3. How to Set Up the Game

**Step 1: Arduino**

1. Connect all the components to the Arduino Mega.
2. Open the Arduino code using Arduino IDE.
3. Select Arduino Mega 2560 and the correct port.
4. Upload the code.

**Step 2: Java**

1. Make sure Java is installed on your computer.
2. Open the Java folder.
3. Run `Run_Reflex_Riot.cmd`.
4. Select the correct COM port and connect to the Arduino.

**Step 3: Play the Game**

1. Choose Solo or 1v1 mode.
2. Press the Ready button.
3. Follow the instructions on the screen.
4. Complete the actions as fast as possible.

## 4. Testing

We tested every component separately before connecting them together. After that, we tested the full system to make sure everything worked correctly.

## 5. Project Files

- **Arduino Folder:** Contains the Arduino code and testing codes.
- **Java Folder:** Contains the game code and audio files.
- **START_HERE.txt:** Contains more detailed instructions.

## 6. Communication

The Arduino sends the detected actions to Java, which updates the game and displays the results.

The project supports USB communication. XBee wireless communication can also be used after proper setup.
