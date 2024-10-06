![WhatsApp Image 2024-10-05 at 10 14 52 PM](https://github.com/user-attachments/assets/6a1b3af0-d464-42ae-8590-535c7f2488a7)

<h2 align="center">Traffic Solution Using Computer Vision (عادِل)</h2>

# ADEL_APP Project - 2024
## Traffic Solution Using Computer Vision (عادِل)
### Optimizing Traffic Flow through Intelligent Signal Management

This project implements a **Smart Traffic Signal System** that optimizes traffic flow based on real-time vehicle density at intersections. The system uses computer vision to detect and classify vehicles, dynamically adjusting signal timings based on the number and type of vehicles present.

---

## 🚗 Key Features
- **Real-time Vehicle Density Measurement**: Continuously detects the number of vehicles at each traffic signal.
- **Weighted Vehicle Prioritization**: Assigns different weights to vehicles (small cars vs. trucks).
- **Dynamic Signal Timing**: Adjusts the green light duration based on vehicle density and types.
- **Traffic Violation Detection**: Monitors illegal lane changes and signals violations.

## 🛠 Technologies Used
- **Computer Vision**: OpenCV
- **Vehicle Detection**: YOLO, PaddleOCR
- **Real-time Processing**: Streamlit for live data visualization
- **Python Libraries**: 
  - OpenCV
  - Numpy
  - Streamlit
  - PaddleOCR
  - Ultralytics (YOLOv5)

---

## 📦 Installation and Setup

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/smart-traffic-signal-system.git
   cd smart-traffic-signal-system


## Problems Faced
1. The ATmega32 has 3 timers. We have used timer1 for the sonar while timer0 for determining the time duration a vehicle remains stand still. That's why we have to use one microcontroller for each lane of any road. This leads to increased number of microcontrollers
2. The systems performs badly if two or more lanes become jam packed. In that case, the system serves only the jam packed roads while the other roads remains unserved.

## Group Members Information
- Mohammed Alrowais 

- Mohammed Al Malki 

- Khaled AlGhamdi 
  
- Waleed AlIkhwan

## Course Teachers
1. Ali H. El-Kassas<br/>
Data Science Instructor,Tuwaiq Academy 

2. Saliyah Alotaibi <br/>
Data Science Instructor,Tuwaiq Academy 

3.Hassan_Algoz <br/>
Data Science Instructor,Tuwaiq Academy 

