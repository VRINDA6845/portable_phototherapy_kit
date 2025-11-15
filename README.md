# portable_phototherapy_kit
Portable Phototherapy Kit – CAD, PCB, Firmware, App, BOM
Portable Phototherapy Kit

This repository contains the complete hardware, firmware, CAD, PCB, and mobile application files for the Portable Neonatal Phototherapy Kit developed at IIT Mandi.
The project focuses on creating a compact, low-cost, and effective device for neonatal jaundice treatment in remote and resource-limited settings.

📁 Repository Structure
portable-phototherapy-kit/
│
├── CAD/
│   └── final_cad.zip              → SolidWorks part & assembly files
│
├── PCB/
│   └── pcb_files.zip              → Schematic & layout
│
├── Firmware/
│   ├── code.ino                   → Main ESP32/Arduino firmware
│   └── src/                       → Additional C++ source files (if any)
│
├── Mobile-App/
│   ├── android/                   → Flutter Android files
│   ├── ios/                       → iOS files
│   ├── lib/                       → Dart source code
│   └── pubspec.yaml               → Flutter dependencies
│
└── BOM/
    └── BOM.xlsx                   → Bill of Materials

🛠️ Project Components
1️⃣ CAD Design (SolidWorks)

Full 3D model of the portable phototherapy enclosure

LED mounting structure

Reflective chamber design

Printable/laser-cuttable parts

2️⃣ PCB Design

LED driver circuitry

Power regulation

ESP32/Arduino interface (if used)

3️⃣ Firmware

Controls LED brightness and timing

Reads sensor inputs

Provides status feedback

4️⃣ Mobile App (Flutter)

Bluetooth/WiFi control (if applicable)

Device monitoring

User interface for settings, timers, logs

5️⃣ Bill of Materials

All mechanical, electrical, and electronic components

Quantity, cost, vendor list

🔧 How to Build / Use
Hardware

3D print/laser cut CAD parts

Assemble optical chamber with reflective sheet

Solder PCB

Install LEDs

Assemble final device

Firmware

Upload code.ino using Arduino IDE or PlatformIO.

Mobile App

Run the following in the app folder:

flutter pub get
flutter run

📜 License

This project is for academic and research purposes.
