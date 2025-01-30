# 🚦 3-Way Traffic Light System with Pedestrian & Vehicle Counter  

## ⚠️ Important Note:
When we built this circuit, we ran into some issues. The **vehicle density counter had a bouncing problem**, meaning it sometimes gave incorrect counts. If you're using this file or making changes, **please check for errors yourself** before finalizing anything.  

## 📌 What This Project Does:
This is a **traffic light controller** for a **3-way intersection**. It has:  
✅ **Traffic Light Control** – Regular traffic light sequence.  
✅ **Pedestrian Button** – Pressing it turns **all lights red for 20 seconds** to let pedestrians cross safely.  
✅ **Vehicle Density Counter** – Uses an **IR sensor** to count cars when they pass.  

## 🛠 How It Works:
1. **Normal Traffic Flow**: The traffic lights change as they normally would.  
2. **Pedestrian Mode**: If someone presses the button, all lights **turn red for 20 seconds**, then the system goes back to normal.  
3. **Car Counting**:  
   - An **IR sensor** is placed under the road.  
   - When a car passes, the sensor **creates a pulse**, increasing the count.  
   - The number of cars counted is displayed on a **7-segment display**.  

## ⚙️ Components Used:
- **74F125, 74LS193, 4017, 4026** – For counting & logic control.  
- **NE555 Timer** – For timing operations.  
- **AND, OR, NOR, NOT, XOR Gates** – For logic operations.  
- **Traffic Lights (LEDs)** – To show signals.  
- **IR Sensor** – To detect cars.  
- **Switches** – To activate pedestrian mode.  

## ⚠️ Known Issues:
- The **vehicle counter sometimes bounces**, meaning it can **miscount cars**. If you're modifying the circuit, you might need **debouncing techniques** to fix this.  
- Always **double-check connections and power supply** to avoid issues.  

## 👥 Team Members:
- **M. Humham Shabbir (4555C)**  
- **M. Umar Khawaja (4567C)**  

## 📂 File Information:
This circuit was made in **Proteus (ISIS Professional)**. If you're working on it, **please verify everything yourself** before making changes.  
