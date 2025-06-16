# 🚦 Traffic Light Simulation – Homework Task 1  
### IEEE CUSB | Control Project  

## 📌 Project Idea  
This project simulates a basic traffic light system using three outputs (Red, Yellow, Green), where **each light is treated as if it controls a motor**.  
The goal is to understand how sequential control works – a core concept in control systems – by simulating real-world behavior like:

- Red → Motor stops (e.g., a gate closes)  
- Yellow → Motor prepares to start  
- Green → Motor runs (e.g., system in motion)

---

## 🕒 Operation Sequence  

| Step               | Red | Yellow | Green |
|--------------------|-----|--------|-------|
| Start              | On  | Off    | Off   |
| After 3 seconds    | On  | On     | Off   |
| After 3 seconds    | Off | Off    | On    |
| After 3 seconds    | Off | Off    | On    |
| Stop               | Off | Off    | Off   |

🔁 The cycle repeats continuously.

---

## 📊 System Flow Diagram  

    +-----------+        +-------------+
    |  Red ON   | -----> |  Motor OFF  |
    +-----------+        +-------------+

    +--------------+     +--------------------+
    | Red + Yellow | --> |  Motor Preparing   |
    +--------------+     +--------------------+

    +-----------+        +-------------+
    | Green ON  | -----> |  Motor ON   |
    +-----------+        +-------------+

---

## 🧠 Control System Perspective  
This simulation is a simple application of **Sequential Control**, where different motors (represented by lights) are triggered step by step based on time.  
It reflects how many real control systems work in automated processes, especially in traffic, gates, and manufacturing lines.

---

## 🎥 Demo Video  
➡️ https://github.com/user-attachments/assets/c11cea5c-053c-41c4-80e7-ede8f8826151

---

## 🙏 Special Thanks  
Big thanks to everyone who supported and guided me in understanding the basics of control systems – especially in applying the concepts practically in this task. Your help made the difference!

