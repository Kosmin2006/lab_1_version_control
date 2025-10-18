# lab_1_version_control

## 📌 Опис проекту
До репозиторію завантажено приклад проекту **AnalogRead_Serial** з дисципліни *Програмування систем IoT (2 курс)*. 
Програма призначена для зчитування аналогового сигналу з потенціометра (або іншого аналогового датчика), підключеного до плати Arduino, та виведення його значення у серійний монітор.

---

### 🔹 Функціональність
- Зчитування даних з аналогового входу **A0** за допомогою функції `analogRead()`. 
- Вивід отриманих значень у **Serial Monitor** через `Serial.println()`. 
- Використання затримки `delay(500)` для зручності спостереження результатів. 

---

### 🔹 Використання
1. Підключити потенціометр до плати Arduino: 
   - середній контакт → **A0**, 
   - крайні контакти → **5V** та **GND**. 
2. Відкрити скетч `AnalogRead_Serial.ino` у середовищі Arduino IDE. 
3. Обрати відповідну плату (Інструменти → Плата) та порт (Інструменти → Порт). 
4. Завантажити код на Arduino. 
5. Відкрити **Serial Monitor** (Ctrl+Shift+M) і спостерігати зміни значень під час обертання потенціометра. 

---

### 🔹 Призначення
Цей проект є навчальним прикладом, який демонструє: 
- основи роботи з аналоговими входами Arduino; 
- взаємодію мікроконтролера з датчиками; 
- вивід даних у серійну консоль для моніторингу; 
- практику зчитування сигналів для побудови IoT-систем. 

# lab_1_version_control (English version)

## 📌 Project Description
This repository contains an example of the **AnalogRead_Serial** project from the *IoT Systems Programming* course (2nd year).
The program is designed to read an analog signal from a potentiometer (or other analog sensor) connected to an Arduino board and display its value in the Serial Monitor.

---

### 🔹 Functionality
- Reading data from analog input **A0** using the `analogRead()` function.
- Outputting received values to the **Serial Monitor** via `Serial.println()`.
- Using `delay(500)` for convenient observation of results.

---

### 🔹 Usage
1. Connect the potentiometer to the Arduino board:
   - middle pin → **A0**,
   - outer pins → **5V** and **GND**.
2. Open the sketch `AnalogRead_Serial.ino` in Arduino IDE.
3. Select the appropriate board (Tools → Board) and port (Tools → Port).
4. Upload the code to Arduino.
5. Open **Serial Monitor** (Ctrl+Shift+M) and observe value changes while rotating the potentiometer.

---

### 🔹 Purpose
This project is an educational example that demonstrates:
- basics of working with Arduino analog inputs;
- microcontroller interaction with sensors;
- data output to serial console for monitoring;
- practice of reading signals for building IoT systems.
