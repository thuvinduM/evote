![Untitled Sketch](https://github.com/user-attachments/assets/9d0d9a64-8051-4946-a872-c2d7d75d0f86)

# Electronic Voting System Using Fingerprint

## Overview
This project is a **biometric-based electronic voting system** that ensures **secure, transparent, and efficient** voting. It authenticates voters using their **fingerprints**, prevents **duplicate voting**, and stores votes securely in EEPROM. The system provides **real-time vote counting** and a user-friendly interface with an **LCD display** and **button-based voting mechanism**.

## Features

### 1. **Secure Voter Authentication**
- Uses a **fingerprint sensor** to verify each voter's identity.
- Ensures **only registered voters** can cast a vote.
- Prevents **duplicate voting** by marking voters who have already voted.

### 2. **Simple and Efficient Voting Process**
- After authentication, the voter selects a candidate using **physical buttons**.
- The vote is stored in **EEPROM memory**, preventing data loss in case of a power failure.

### 3. **Real-time Vote Counting & Results Display**
- The system tracks and updates **votes for each candidate**.
- Results can be viewed on an **LCD screen** at any time.
- If a voter attempts to vote again, the system notifies them that they have **already voted**.

### 4. **Admin Controls for System Management**
- **Enroll voters**: Admins can register new voters by storing their fingerprints.
- **Delete voters**: Admins can remove registered fingerprints.
- **System Reset**: Clears all vote records and resets the system.

### 5. **Alerts and Indications**
- A **buzzer** and **LED indicators** provide feedback for authentication, vote submission, and errors.
- **LCD messages** guide users through the voting process.

## Hardware Components
- **Microcontroller** (Arduino or similar)
- **Fingerprint Sensor** (R307 or similar)
- **Push Buttons** (for candidate selection)
- **EEPROM** (for storing votes)
- **16x2 LCD Display** (for user interaction)
- **Buzzer & LEDs** (for alerts and feedback)
- **Power Supply**

## Software Requirements
- **Arduino IDE** (for programming the microcontroller)
- **Fingerprint Sensor Library**
- **EEPROM Library**

## Setup Instructions
1. **Connect the hardware components** according to the circuit diagram.
2. **Upload the Arduino code** to the microcontroller.
3. **Register voters** using fingerprint enrollment.
4. **Start the voting process** – each voter authenticates and selects a candidate.
5. **View election results** on the LCD display.

## Applications
✅ **School/College Elections** – Secure and automated student elections.  
✅ **Small-Scale Organizational Voting** – Efficient voting in clubs, associations, or private groups.  
✅ **Community Decision Making** – Secure voting for local communities or gated societies.  
✅ **Preliminary Testing for Large-Scale Electronic Voting** – A base model for official elections.  

## Future Enhancements
- **Internet Connectivity** – Integrate IoT for remote voting and real-time data access.
- **Database Integration** – Store voter data and election results in a cloud database.
- **Touchscreen Interface** – Replace buttons with a graphical voting interface.

## License
This project is open-source. Feel free to modify and improve it for educational and research purposes.

![Untitled Sketch](https://github.com/user-attachments/assets/b60498a3-b4a0-42a6-85f8-6f4d04e231de)
