# Text Communication Using Light Fidelity  

## Overview  
This repository showcases a project on **Text Communication Using Light Fidelity (Li-Fi)**, where text messages are transmitted using visible light. The project includes a **performance analysis of Li-Fi** in comparison with Wi-Fi and explores how external light sources affect its performance. The system has been tested in three distinct environments, demonstrating its reliability and efficiency in varied lighting conditions.  

## Features  
- **Performance Analysis:**  
  - Evaluates Li-Fi's performance in the presence and absence of external light sources.  
  - Compares Li-Fi with traditional Wi-Fi technology in terms of speed, reliability, and security.  
- **Secure Text Transmission:**  
  - Utilizes visible light for secure communication, ensuring that data remains inaccessible outside the line of sight (LOS).  
- **Environment Testing:**  
  - Conducted experiments in indoor and outdoor environments to validate system robustness.  
- **Synchronization:**  
  - Achieved smooth communication by introducing a **5ms delay** on both transmitter and receiver sides.  

## Workflow  
1. **Text Input:** Text messages are input via a keyboard or a predefined text source.  
2. **Modulation:** The text is encoded into a light signal using the transmitter.  
3. **Transmission:** A laser module transmits the modulated light signal to the receiver.  
4. **Reception:** The solar panel detects the light signal and demodulates it into text.  
5. **Output:** The transmitted text is displayed on a screen or stored for further analysis.  

## Environment Testbeds  
1. **Indoor Environment (Without External Light):**  
   - Controlled environment to test the ideal performance of Li-Fi.  
2. **Indoor Environment (With External Light Sources):**  
   - Tests the impact of ambient light interference on Li-Fi communication.  
3. **Outdoor Environment:**  
   - Evaluates the system's performance in natural lighting conditions.  

## Applications  
- **Secure Communication:** Ensures privacy as light-based signals do not pass through walls.  
- **Indoor IoT Communication:** Facilitates fast and secure communication in smart homes or offices.  
- **Text-Based Messaging Systems:** Reliable for short-range, high-security applications.  
- **Industrial Use:** Efficient communication in areas where radio frequency signals face interference.  

## Requirements  
- **Hardware:**  
  - Laser module for text signal transmission  
  - Solar panel for light signal reception  
  - Microcontrollers for text encoding and decoding  
  - Power supply for the circuits  
  - Display device (e.g., LCD or computer screen) for output  

- **Software:**  
  - Arduino IDE for microcontroller programming  
  - Serial communication software (if needed for additional debugging)  

## How to Use  
1. Clone this repository:  
   ```bash  
   git clone https://github.com/your-username/Text-Communication-Using-Li-Fi.git  
