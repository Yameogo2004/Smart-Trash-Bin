# 🗑️ Smart Trash Bin

## 📌 Description
The **Smart Trash Bin** is an Arduino-based embedded system designed to automate waste disposal.
The trash bin automatically opens its lid when motion is detected and prevents opening when it is full using a weight sensor.

This project combines sensors, actuators, and microcontroller logic to provide a simple and efficient smart waste management solution.

---

## ⚙️ Features
- Automatic lid opening using motion detection
- Weight sensing to detect when the bin is full
- Lid locking mechanism when maximum weight is reached
- Manual reset using a push button
- Low-cost and easy-to-implement embedded system

---

## 🧰 Hardware Components
- Arduino Uno / Arduino Nano
- Servo motor (for lid control)
- Motion sensor
- Load cell + HX711 weight sensor module
- RFID module (RC522)
- Push button (weight reset)
- Power supply and wiring

---

## 🧠 System Working Principle
1. The motion sensor detects the presence of a hand or object.
2. The Arduino checks the current weight of the trash bin.
3. If the detected distance is valid **and** the bin is not full, the servo motor opens the lid.
4. If the bin is full, the lid remains closed.
5. A push button allows manual weight reset after emptying the bin.

---

## 📁 Project Structure

report/ # Technical report PDF

hardware/ # Circuit diagrams and component details

media/
images/ # Photos of the prototype
videos/ # Demo videos or links

README.md


## 👤 Author

Ariel Yameogo
Etudiant en Reseaux & Telecommunications


