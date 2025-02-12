# ![Screenshot 2025-01-24 113947](https://github.com/user-attachments/assets/3c24cd87-d202-40b8-8882-7cf21922c1f2)



# VitaBeat – AI-Powered Heart Attack Detection Device  

## Overview  
There is a pressing need for a dedicated, portable device that can predict the probability of a heart attack in real-time. This device should be easy to use, affordable, and capable of providing actionable insights, empowering users to seek timely medical intervention.

VitaBeat is a compact, AI-powered device designed for real-time heart attack risk detection, similar to a glucometer. It requires no cloud storage and instantly analyzes heart health to alert users of potential risks.  

## Features  
- 📟 **Portable Design** – Works like a glucometer for heart attack risk detection.  
- 🔬 **AI-Powered Analysis** – Uses advanced algorithms to identify early warning signs.  
- ⚡ **Instant Results** – Provides immediate feedback without internet dependency.  
- 🔋 **Battery-Operated** – Can function in remote and rural areas.  

## Technology Stack  

### Hardware Components:  
- ECG Sensor  
- Microcontroller (ESP32/Raspberry Pi Pico)  
- OLED Display  
- Rechargeable Battery  
- Finger Clip Sensor  

### Software & AI:  
- Machine Learning Model for Heart Attack Risk Prediction  
- Google Gemini APIs for Data Interpretation  
- IDX Google for Development  

## Implementation Cost (Estimated)

For a detailed cost breakdown, check the **(Hardware.md)**.

  
## How to Use the VitaBeat Device  

### **Step 1: Power On the Device**  
- Press and hold the **power button** to turn on the device.  
- The screen will show a **blinking red LED** indicating it’s ready.  

### **Step 2: Perform the Blood Test (Main Test Method)**  
- Wash hands with clean water.  
- Place your **finger on the built-in prick system** and press the **"Prick" button** (like a glucometer).  
- A small drop of blood will appear.  
- **Touch the blood drop to the test strip** and insert it into the device.  
- The device will analyze **Troponin-I levels** (a key heart attack biomarker).  

### **Step 3: Optional ECG & PPG Check (For More Accuracy)**  
- While the blood test is running, place your **finger on the ECG/PPG sensor pad**.  
- The device will measure **heart activity and blood flow patterns**.  
- This step is **optional** but can provide additional heart health insights.  

### **Step 4: View the Results**  
- After **10-15 seconds**, the screen will display the **heart attack risk status**:  
  - ✅ **Green LED:** Normal heart health (Safe).  
  - ⚠️ **Yellow LED:** Moderate risk (Monitor your health).  
  - 🚨 **Red LED + Beep:** High risk detected – **Seek medical help immediately**.  

### **Step 5: Auto-Eject & Power Off**  
- The device will **automatically eject the used test strip** – **DO NOT reuse it**.  
- Press and hold the **power button** for 3 seconds to turn off the device.  
- Store it in a **safe, dry place** for future use.  



This version is now **simplified for rural users** by:    
✔️ Making the **prick process automatic** to avoid confusion.  
✔️ Using **color-based LED alerts** instead of complex instructions.  
✔️ **Auto-ejecting the test strip** to prevent reuse.  
  

## License  
This project is licensed under the **Apache License 2.0**. See the `LICENSE` file for details.  

