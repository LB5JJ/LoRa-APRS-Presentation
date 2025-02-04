# LoRa APRS: Long-Range, Low-Power Communication

Note: This is the Markdown version of my presentation

## Long-Range Tracking and Messaging on 433 MHz

**LB5JJ**  
[https://lb5jj.no/aprs/lora/](https://lb5jj.no/aprs/lora/)

---

## Introduction

### What is APRS?
- Automatic Packet Reporting System
- Tracking and messaging in amateur radio
- Mostly used on 144.800 MHz (let's change that)

### What is APRS for?
- Tracking
- Messaging
- Weather station and other sensors

---

## Introduction to LoRa

### What is LoRa?
- Long Range, Low Power wireless technology
- Based on Chirp Spread Spectrum (CSS) modulation

### LoRa Properties
- Long-range communication (100+ km in open areas)
- Low power consumption

---

## What is LoRa APRS?

### Combining LoRa and APRS
- Advantages over traditional APRS
  - Greater range with lower power
  - Suitable for modern, low-cost hardware
  - Enhanced reliability in challenging environments

---

## Hardware

- SX1276/78
- Arduino, ESP32
- GPS receivers for position tracking
- Pre-built modules with all 3 functions on one PCB

---

## Software Components

- Ricardo Guzman (CA2RXU) firmware:
  - Tracker
  - iGate/Digipeater
- APRS.fi app for iPhone (BLE)
- APRSDroid for Android (BLE)
- PinPoint APRS for Windows (BLE, USB Serial or WiFi)

---

## How LoRa APRS Works

1. Get position from GPS, or;
2. Enter message on phone or keyboard
3. Encode as APRS message
4. Packet sent over LoRa
5. Repeated by Digipeaters
6. Relayed via the Internet by iGates
7. Received by other LoRa APRS devices

---

## Applications and Use Cases

- Adventure tracking (SOTA, POTA, Hiking)
- Off-grid messaging
- Disaster and emergency communication and tracking
- Monitoring weather stations and other sensors:
  - Alarms
  - Temperature
  - Battery voltage
  - Others

---

## Setting Up Your LoRa APRS System

- Acquire LoRa module (eBay, AliExpress, etc)
- Install firmware (Web installer for Guzman Firmware)
- Configure (Web config for Guzman Firmware)
- Connect to APRS-IS (for iGate)
- Connect to phone / PC (Optional; for tracking/messaging)

---

## Challenges and Limitations

### Regulatory restrictions and frequency allocation
- Up to 200 kHz bandwidth between 433.600 and 434.000 MHz now allowed in Norway
- LoRa APRS sits on 433.775 MHz and uses 125 kHz bandwidth

### LoRa network congestion / limited bandwidth
- Only about 1/7th the transfer rate of 1200 Baud packet
- Keep your transmissions as short as possible!

---

## Links, and thanks for listening

- [https://github.com/richonguzman/LoRa_APRS_Tracker](https://github.com/richonguzman/LoRa_APRS_Tracker)
- [https://github.com/richonguzman/LoRa_APRS_iGate](https://github.com/richonguzman/LoRa_APRS_iGate)
- [https://lilygo.cc/](https://lilygo.cc/)
- [https://lora-aprs.live/](https://lora-aprs.live/)
- [https://aprs.fi/](https://aprs.fi/)
- [https://lb5jj.no/aprs/lora/](https://lb5jj.no/aprs/lora/)
- cq@lb5jj.no

