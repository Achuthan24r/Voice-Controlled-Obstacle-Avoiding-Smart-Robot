# Voice Controlled + Obstacle Avoiding Smart Robot 🤖🎤

## 📌 Project Overview
This project is a smart robotic vehicle controlled via voice commands using Bluetooth.  
It also features automatic obstacle detection and avoidance using an ultrasonic sensor.

The robot can operate in:
- Manual Mode (Voice Control)
- Auto Mode (Obstacle Avoidance)

---

## 🚀 Features

- 🎤 Voice control via mobile app
- 📡 Bluetooth communication (HC-05)
- 🚧 Obstacle detection (HC-SR04)
- 🔄 Automatic avoidance logic
- 🔁 Manual / Auto mode switching
- ⚡ Real-time motor control

---

## 🧩 Hardware Components

- Arduino UNO
- L298N Motor Driver
- HC-05 Bluetooth Module
- Ultrasonic Sensor (HC-SR04)
- DC Motors + Chassis
- Battery (7V–12V)
- Jumper wires

---

## 🔌 Pin Configuration

### Motor Driver (L298N)

| L298N | Arduino |
|--------|----------|
| ENA | D5 |
| ENB | D6 |
| IN1 | D7 |
| IN2 | D8 |
| IN3 | D9 |
| IN4 | D10 |

### Ultrasonic Sensor

| HC-SR04 | Arduino |
|-----------|----------|
| TRIG | D11 |
| ECHO | D12 |

### Bluetooth Module (HC-05)

| HC-05 | Arduino |
|----------|----------|
| TX | RX (D0) |
| RX | TX (D1) *(Use voltage divider)* |
| VCC | 5V |
| GND | GND |

---

## 🖼️ Circuit Diagram

Below is the circuit diagram for the project:

![Circuit Diagram](A_circuit_diagram_in_the_digital_illustration_show.png)

(Ensure this image file is placed in the same GitHub folder as README)

---

## 🧠 Working Principle

1. Mobile app converts voice into text commands.
2. Bluetooth sends command to Arduino.
3. Arduino processes command and controls motors.
4. Ultrasonic sensor constantly checks for obstacles.
5. If obstacle detected in Auto Mode → robot avoids it automatically.

---

## 🎮 Voice Command Mapping

| Voice Command | Character Sent |
|----------------|----------------|
| Forward | F |
| Backward | B |
| Left | L |
| Right | R |
| Stop | S |
| Auto Mode | A |
| Manual Mode | M |

---

## 🔄 Modes

### Manual Mode
Robot moves based on voice commands.

### Auto Mode
Robot moves forward automatically and avoids obstacles.

---

## 🌍 Applications

- Smart robotics learning
- Voice-based automation
- Assistive robotics
- Hackathons & exhibitions

---

## 🔮 Future Enhancements

- ESP32 WiFi dashboard
- Camera streaming
- Fire & gas detection
- GPS tracking
- AI voice recognition

---

## 👨‍💻 Author
Achuthan Rameshkumar
# Voice-Controlled-Obstacle-Avoiding-Smart-Robot
