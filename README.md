# Smart Hotel Room Service & Automation System 🏨🛎️

A virtual instrumentation application designed to simulate and manage automated room service requests, climate control, and security for modern hotel rooms. 

This project was developed using **NI LabVIEW** for the **Instrumentation and Measurement** course at **Addis Ababa Science and Technology University (AASTU)**.

## 🎯 Project Overview
The objective of this project is to automate real-world control systems using simulated sensors and logic. The digital Human-Machine Interface (HMI) allows guests to order food, controls the room temperature automatically, and provides a security/fire alarm system monitored via a central hotel display.

## 📥 System Inputs
* **Room Temperature Sensor:** Detects the current temperature of the room.
* **Smoke Sensor:** Continuously monitors the smoke level for fire safety.
* **Keypad:** A secure digital pad where the user enters a password to unlock the door.
* **Order Buttons & Quantity Selectors:** Allows guests to order food items (e.g., Cheesecake, Chocolate Cake).

## ⚙️ Subsystems & Logic Processing
* **Temperature Control Logic:** Compares the live sensor value to the user-defined set point. If the temp is higher than the set point, it activates the AC. If lower, it activates the Heater.
* **Smoke Detection & Door Lock:** If smoke exceeds 70%, it triggers emergency alarms and blinking LEDs. The door lock logic ensures access is only granted with the correct password.
* **Food Ordering & Billing Module:** Calculates the total bill based on selected quantities. It automatically applies dynamic discounts (5%, 10%, or 15%) based on the total cost, and displays an order confirmation.

## 📤 System Outputs
* **Heater / Air Conditioner:** Visual LED indicators showing active climate control.
* **Emergency Indicators & Alarm:** Visual safety status (Emergency R1) on the Hotel Display.
* **Door Lock Actuator:** Visual indicator showing "Door Locked" or unlocked state.
* **Order Confirmation Display:** Shows total bill, applied discount, and estimated preparation time.

## 🚀 How to Run the Application
1. Clone this repository to your local machine.
2. Ensure you have **NI LabVIEW** installed on your computer.
3. Open the `.vi` file included in this repository.
4. Click the **Run** arrow (or press `Ctrl + R`) on the top toolbar.
5. Interact with the Front Panel controls (temperature sliders, smoke dial, keypad, and food order buttons) to simulate guest inputs and observe the automated system responses!


## 👥 Team Members
**Addis Ababa Science and Technology University (AASTU)**  
*College of Engineering | Electro-Mechanical Engineering Department*

* **Desalegn Lulie**
