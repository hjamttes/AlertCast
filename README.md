# AlertCast

## Description
AlertCast is a dual-phone system that uses a private SIP server to send automated voice alerts and updates. One phone is used for alerts while the other handles general information, and users can dial extensions to trigger messages between them.

## Why I Made This
I wanted to explore how phone systems work and combine analog and IP phones with automation to create a simple notification system.

## Features
- Dual-channel messaging (alerts + updates)
- Analog + IP phone integration
- Extension-based interaction
- Automated text-to-speech playback

## System Overview
- Raspberry Pi runs Asterisk PBX
- IP phone connects via SIP
- Analog phone connects via ATA
- Python scripts trigger calls and playback

## Images
!(diagram/SystemDiagram.png)

## Wiring Diagram
(Add your wiring diagram image here)

## 3D Model
(Add screenshot of CAD model here)

## BOM

| Item | Quantity | Price | Link |
|------|--------|------|------|
| Raspberry Pi 4 (4GB) | 1 | $65 | link |
| Cisco SPA122 ATA | 1 | $45 | link |
| MicroSD Card 32GB | 1 | $10 | link |
| Ethernet Cable | 2 | $10 | link |
