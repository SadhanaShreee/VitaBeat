# VitaBeat Hardware Documentation

## Overview

VitaBeat is a portable, real-time heart attack detection device that analyzes heart health using a combination of ECG, PPG, and blood biomarker sensors. It functions similarly to a glucometer, providing instant results without cloud storage.

## Implementation Cost (Estimated)

| Component                                 | Estimated Cost (INR)  |
|-------------------------------------------|-----------------------|
| **Microcontroller (ESP32/STM32)**         | ₹500 – ₹1,500        |
| **ECG Sensor Module (AD8232)**            | ₹900 – ₹1,800        |
| **Photoplethysmography (PPG) Sensor**     | ₹300 – ₹700         |
| **OLED/LCD Display**                      | ₹500 – ₹1,200       |
| **Rechargeable Battery**                  | ₹300 – ₹600         |
| **3D-Printed Casing**                     | ₹700 – ₹1,500       |
| **PCB Manufacturing & Assembly**          | ₹1,000 – ₹3,000     |
| **Firmware Development**                  | ₹5,000 – ₹12,000    |
| **Testing & Calibration**                 | ₹2,000 – ₹5,000     |
| **Blood Biomarker Test Strip (Troponin Detection)** | ₹500 – ₹1,500 |
| **Miscellaneous Components & Assembly**   | ₹1,500 – ₹4,000     |

### **Total Estimated Cost:** ₹13,200 – ₹33,800


## Working Mechanism

| Component                              | Function |
|----------------------------------------|------------------------------------------------|
| **ECG Sensor (AD8232)**                | Captures heart electrical activity to detect irregular rhythms. |
| **PPG Sensor**                         | Monitors blood flow changes to detect pulse irregularities. |
| **Blood Biomarker Test Strip**         | Detects Troponin-I, a key heart attack biomarker, for improved accuracy. |
| **Microcontroller (ESP32/STM32)**      | Processes sensor data and displays results. |
| **OLED/LCD Display**                   | Shows real-time analysis without cloud dependency. |

## Why Use a Blood Biomarker Test Strip?

| Reason | Explanation |
|--------------------|----------------------------------------------------------------|
| **ECG & PPG alone may not detect all heart attacks** | Especially silent heart attacks that do not show strong ECG abnormalities. |
| **Troponin-I detection** | A medical standard for accurate heart attack diagnosis. |
| **Combining sensor data with a biomarker test** | Enhances reliability and improves early detection accuracy. |

## Prototype Development Plan

| Phase  | Description |
|--------|----------------------------------------------|
| **Phase 1** | Develop ECG + PPG-based heart monitoring system. |
| **Phase 2** | Integrate Troponin-I blood test strip for enhanced detection. |
| **Phase 3** | Optimize firmware for efficient real-time analysis. |
| **Phase 4** | Test accuracy against standard ECG & biomarker devices. |

## Future Improvements

| Improvement | Benefit |
|-------------------------|------------------------------------------------------------|
| **Multi-lead ECG integration** | Improves precision in detecting cardiac issues. |
| **Wireless connectivity** | Enables real-time alerts to emergency contacts. |
| **AI-powered risk prediction model** | Provides early warnings based on historical health data. |

## Conclusion

VitaBeat aims to provide a **cost-effective, portable solution** for early heart attack detection by combining **ECG, PPG, and biomarker analysis**. This hybrid approach ensures **higher accuracy** than traditional wearable heart monitors.  
