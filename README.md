# STM32-Nucleo-64-I2C-Protocol 🚀

This project demonstrates a successful implementation of **I2C communication** between **two STM32 Nucleo-64 boards**, where:

- 🧠 **One board acts as the Master**
- 🤖 **The other board acts as the Slave**

It’s a clean, practical setup showing how to send and receive data using the I2C protocol, widely used in embedded systems for reliable device-to-device communication.

---

## 🛠️ Hardware Requirements

- 2x STM32 Nucleo-64 boards (e.g., NUCLEO-F401RE, NUCLEO-L476RG, etc.)
- Jumper wires (Female-to-Female)
- Common GND between both boards

---

## 🔌 I2C Wiring Diagram

| Master Pin | Connection | Slave Pin |
|------------|------------|------------|
| SDA        | <--------> | SDA        |
| SCL        | <--------> | SCL        |
| GND        | <--------> | GND        |

- **SDA**: Data line
- **SCL**: Clock line
- Make sure pull-up resistors (~4.7kΩ) are used if not already on the board.

---

## 📦 Project Structure

