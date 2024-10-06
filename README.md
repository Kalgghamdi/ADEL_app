![WhatsApp Image 2024-10-05 at 10 14 52 PM](https://github.com/user-attachments/assets/6a1b3af0-d464-42ae-8590-535c7f2488a7)

<h2 align="center">Traffic Solution Using Computer Vision (عادِل)</h2>

# ADEL_APP Project - 2024
# Traffic Solution Using Computer Vision (عادِل)
## **Optimizing Traffic Flow through Intelligent Signal Management**

## Project Overview
This project is aimed at developing a **Smart Traffic Signal System** that optimizes the flow of traffic based on real-time vehicle density at intersections. The system dynamically adjusts signal priorities to give more time to the direction with higher vehicle density. By assigning vehicles a default weight based on their type (e.g., cars, trucks), the system allocates signal time in a way that balances traffic efficiency.

For example:
- **Small cars** are given a weight of 1.
- **Large trucks** are assigned a weight of 2.

This allows for a more realistic distribution of signal time, ensuring that both light and heavy vehicles are accounted for. If an intersection has a total signal time of 2 minutes, the system will allocate 20 seconds for each signal, adjusting based on traffic conditions to optimize flow.

## Key Features
- **Real-time vehicle density measurement**: Detects the number of vehicles at each signal.
- **Weighted vehicle prioritization**: Adjusts signal time based on vehicle type (e.g., small cars vs. large trucks).
- **Dynamic signal timing**: Allocates more time to directions with higher traffic, reducing congestion and wait time.

## Vision 2030 Alignment
This project supports **Saudi Vision 2030**, which seeks to enhance urban infrastructure and improve the quality of life through the integration of smart technologies. By improving traffic flow, the **Smart Traffic Signal System** helps in:
- Reducing traffic congestion.
- Lowering carbon emissions.
- Enhancing the daily commuting experience.

The system also contributes to the development of **smart cities** that use intelligent solutions to manage resources efficiently, aligning with the broader goals of Vision 2030.

## Benefits
- **Time Efficiency**: Reduces wait times at intersections, improving overall traffic flow.
- **Environmental Impact**: Lower idle times at signals can contribute to reduced fuel consumption and emissions.
- **Scalability**: Can be adapted for use in cities with different traffic patterns and densities.
- **Flexibility**: Signal timings can be easily modified based on changes in traffic behavior, ensuring long-term effectiveness.

## Getting Started
To set up the project on your local machine:
1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/smart-traffic-signal-system.git

## Install dependencies:
cd smart-traffic-signal-system
npm install

## Run the application:
npm start

## ✨ Features
The **Smart Traffic Signal System** offers several key features that contribute to more efficient and intelligent traffic management:

- **Real-time Vehicle Density Monitoring**: Continuously detects the number of vehicles at each traffic light, ensuring the system adapts to live traffic conditions.
  
- **Weighted Vehicle Prioritization**: Assigns different weights to vehicles based on their type, such as:
  - Small cars (weight = 1)
  - Large trucks (weight = 2)
  This allows for more balanced signal timing, giving heavier traffic more attention without ignoring smaller vehicles.

- **Dynamic Signal Timing Adjustment**: Automatically adjusts the duration of green, yellow, and red lights based on vehicle density and weights, reducing congestion during peak hours and enhancing traffic flow during quieter times.

- **Fair Time Distribution**: If a total signal time of 2 minutes is set for an intersection, the system distributes the time fairly across all directions while considering vehicle density, ensuring smoother movement across all lanes.

- **Customizable for Different Cities**: The system can be configured to suit different urban traffic conditions and can easily adapt to varying vehicle types and traffic patterns.

- **Environmental Impact**: Reducing idle time at traffic signals not only improves traffic flow but also cuts down on fuel consumption and emissions, making the system more eco-friendly.

- **Integration with IoT and Smart Cities**: Supports integration with IoT devices and smart city infrastructure, enabling further enhancements like communicating with autonomous vehicles and traffic management centers.

- **Scalability**: Can be scaled from small city intersections to large metropolitan areas with multiple intersections, offering flexibility as cities grow and traffic demands increase.

These features make the system highly adaptable and efficient in improving both traffic flow and urban mobility.

## 🛠 Problems Faced
During the development of the **Smart Traffic Signal System**, we encountered a few challenges:

- **Real-time Data Accuracy**: Ensuring precise vehicle detection and classification under varying weather and traffic conditions.
- **Balancing Traffic Flow**: Achieving an optimal signal timing for all directions without creating delays in less congested areas.
- **Infrastructure Integration**: Adapting the system to work seamlessly with older traffic signal infrastructure required additional hardware and software adjustments.
- **Scalability**: Expanding the system for larger cities posed challenges in maintaining real-time performance across multiple intersections.
- **Data Privacy**: Ensuring that real-time monitoring respects privacy laws and secures data was a priority.

Despite these challenges, we managed to overcome them through continuous testing and system optimization.

## Libraries Used

1. streamlit
2. opencv-python
3. Pillow
4. numpy
5. moviepy
6. imageio[ffmpeg]
7. inference-sdk
8. ultralytics
9. deep_sort_realtime
10. imageio
11. paddlepaddle
12. paddleocr
13. matplotlib
14. pandas




- 📫 How to reach me **kalgghamdi@gmail.com**

<h3 align="left">Connect with me:</h3>
<p align="left">
<a href="https://linkedin.com/in/https://www.linkedin.com/in/khaled-alghamdi-b33718a5/" target="blank"><img align="center" src="https://raw.githubusercontent.com/rahuldkjain/github-profile-readme-generator/master/src/images/icons/Social/linked-in-alt.svg" alt="https://www.linkedin.com/in/khaled-alghamdi-b33718a5/" height="30" width="40" /></a>
</p>

<h3 align="left">Languages and Tools:</h3>
<p align="left"> <a href="https://ifttt.com/" target="_blank" rel="noreferrer"> <img src="https://www.vectorlogo.zone/logos/ifttt/ifttt-ar21.svg" alt="ifttt" width="40" height="40"/> </a> <a href="https://www.mysql.com/" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/mysql/mysql-original-wordmark.svg" alt="mysql" width="40" height="40"/> </a> <a href="https://www.python.org" target="_blank" rel="noreferrer"> <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/python/python-original.svg" alt="python" width="40" height="40"/> </a> </p>







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

