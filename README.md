#  Digital Visitor Counter using 8051 Microcontroller

A smart embedded system to help prevent overcrowding at public places like **airports, malls, and museums** by automatically counting people entering and exiting a facility.

This project was developed as part of the **Embedded Systems** course under the guidance of **Dr. Emad Badry**, using the **AT89C51** microcontroller and simulated on **Proteus**.

---

##  Project Objective

Build an automatic visitor counting system that:
- Detects real-time **entry and exit**
- Displays the number of people currently inside
- Triggers **alerts** when a safety limit is reached
- Operates even during **power outages**

---

## ⚙️ System Components

| Component         | Description                                      |
|------------------|--------------------------------------------------|
| **AT89C51**       | 8051-based microcontroller for control logic     |
| **2 IR Sensors**  | Detect person entry and exit                     |
| **16x2 LCD**      | Displays live count                              |
| **Buzzer + LED**  | Alert system when limit is exceeded              |
| **Buttons**       | For manual reset/testing                         |
| **Battery Backup**| Rechargeable system to maintain power reliability|

---

##  How It Works

1. **Entry/Exit Detection** – Two IR sensors track people entering and exiting.
2. **Real-Time Counting** – Microcontroller updates the count accordingly.
3. **Display Output** – LCD shows the current number of visitors.
4. **Overcrowding Alert** – When a preset limit is reached, a buzzer and LED go off.
5. **Power Fail Safe** – Rechargeable battery ensures functionality during outages.

---

## 💻 Code Features

- Detect IR sensor triggers in real-time
- Dynamically update visitor count on LCD
- Trigger buzzer/LED when max limit is reached
- Simulate edge cases for accuracy (e.g., multiple entries at once)

---

## 📽️ Simulation

> 🔧 The full hardware simulation was implemented in **Proteus**.  
> 🎥 A video demonstration is included to show the system in action.  
> *(Upload your simulation video to the repo or link it here)*

---

##  Team Members

- Rana Nader  
- Mohamed Elhosiny  
- Ahmed Sameh  
- Khaled Elsharkawy  
- Roya Hany  
- Mahmoud Ahmed  
- Al-Zahraa Soliman  
- Ahmed Sameer  
- Mazin Hytham  

---

##  Supervisor

**Dr. Emad Badry**  
Embedded Systems Instructor

---

## 📁 Repository Structure

