# Medicine-Reminder

## 📌 Project Overview

This project implements a **Medicine Reminder System** using the **LPC2148 ARM7 microcontroller**.
It is designed to help patients or elderly people take their medicines on time by providing reminders through **LCD display, buzzer**.

The system uses **RTC (Real Time Clock)** to track time and trigger reminders based on the stored schedule. The user can set the medicine time using a **keypad**, and the system will automatically alert at the scheduled time.

## ⚙️ Features

* Real-time clock (RTC DS1307 / inbuilt RTC) for accurate timekeeping
* Keypad-based medicine schedule entry
* LCD (16x2) display for user interface
* Buzzer alarm for reminders

## 🛠️ Hardware Requirements

* **LPC2148 ARM7 Microcontroller**
* 16x2 LCD Display
* 4x4 Matrix Keypad
* RTC (DS1307 or LPC2148 inbuilt RTC)
* Buzzer
* Power Supply (5V regulated)
  
## 🧩 Software Requirements

* Keil µVision / ARM GCC Toolchain
* Flash Magic (for programming LPC2148)
* Proteus (for simulation)

## 📐 Working Principle

1. User sets medicine timings through the keypad.
2. The timings are stored in EEPROM and tracked using RTC.
3. At the scheduled time:

   * The buzzer rings.
   * LCD shows the reminder message (e.g., *“Take Medicine 1”*).
   * (Optional) GSM sends an SMS reminder.
4. User acknowledges by pressing a key, stopping the buzzer.

## 🔑 Applications

* Elderly care
* Hospital patient medicine tracking
* Home healthcare systems
* IoT-based health monitoring (future scope)

## 🚀 Future Enhancements

* Android app integration for remote reminders
* IoT-enabled medicine tracking
* Automatic pill dispenser mechanism
  
 

