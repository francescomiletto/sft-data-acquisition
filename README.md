# ONDA v2.5 — SuMoth Data Acquisition System

<img src="https://github.com/user-attachments/assets/0174e8e6-0792-46dd-83ef-8188031583d2" width="400" alt="1788624298226">

## 🇬🇧 English Description

### Overview
**ONDA v2.5** is a custom compact telemetry and data logging board designed for the **Sapienza Foiling Team** to equip their hydrofoil sailing boat competing in the international **SuMoth Challenge**. 

Built around the **ESP32-S3** microcontroller, the board processes real-time dynamics and navigation data from a 9-axis Inertial Measurement Unit (IMU) and a high-precision GPS module. Logged data is stored on an onboard microSD card for post-race analysis and transmitted via Wi-Fi for real-time telemetry display.

### System Architecture & Features
* **Main Controller:** ESP32-S3 dual-core microcontroller handling high-speed data acquisition and wireless communications.
* **Navigation & Dynamics Tracking:**
  * **IMU (9-Axis):** I2C interface (SCL/SDA) for high-frequency motion tracking (pitch, roll, yaw, linear accelerations).
  * **GPS Module:** Dedicated UART interface for speed, heading, and spatial positioning.
* **Data Storage:** High-speed SPI interface connected to a microSD card module for local session logging and data backup.
* **Power Management Stage:** Integrated Buck regulator (3.3V) enabling direct power supply from an onboard LiPo battery system.
* **User Interface & Diagnostics:** Integrated Master Switch, hardware Reset & Function buttons, and status LEDs for power, system boot, and GPS fix indication.

---

## 🇮🇹 Descrizione in Italiano

### Panoramica
**ONDA v2.5** è una scheda personalizzata di acquisizione dati e telemetria progettata per l'imbarcazione a vela hydrofoil del **Sapienza Foiling Team**, partecipante alla competizione internazionale **SuMoth Challenge**.

Basata sul microcontrollore **ESP32-S3**, la scheda acquisisce e processa in tempo reale i dati dinamici e di navigazione forniti da una piattaforma inerziale (IMU a 9 assi) e da un modulo GPS ad alta precisione. I dati raccolti vengono salvati su una scheda microSD per l'analisi post-regata e trasmessi via Wi-Fi per la visualizzazione della telemetria in tempo reale.

### Architettura e Caratteristiche Tecniche
* **Unità di Calcolo:** Microcontrollore ESP32-S3 dual-core per la gestione simultanea dell'acquisizione sensori ad alta frequenza e delle comunicazioni wireless.
* **Tracciamento Dinamico e Posizionamento:**
  * **IMU (9 Assi):** Interfaccia I2C per il tracciamento ad alta frequenza dell'assetto dello scafo (rollio, beccheggio, imbardata e accelerazioni).
  * **Modulo GPS:** Interfaccia UART dedicata per il calcolo della posizione, velocità e rotta.
* **Memorizzazione Dati:** Bus SPI ad alta velocità collegato a modulo microSD integrato per il salvataggio continuo dei log di sessione.
* **Stadio di Alimentazione:** Modulo di potenza Buck integrato (3.3V) per l'alimentazione diretta tramite pacco batterie LiPo di bordo.
* **Interfaccia Utente e Diagnostica:** Interruttore principale (Master Switch), pulsanti fisici di controllo/reset e LED di stato dedicati per l'indicazione di alimentazione, avvio sistema e fix GPS.

---

## 📐 System Schematics & PCB Layout / Schemi e Layout PCB

### Connection Block Diagram / Schema Elettrico di Connessione
<img width="600" alt="SCHEMA" src="https://github.com/user-attachments/assets/c1636733-7222-4234-864f-4a9a7fb51d4f" />

### 3D CAD Board Model / Modello 3D PCB
<img width="1289" height="785" alt="3D Scheda Sumoth" src="https://github.com/user-attachments/assets/0442a888-f010-415f-b512-a0a4a6e810ed" />

---

## 🎬 Video & Attachments / Video e Allegati

* 🎥 **Hardware Demonstration Video:** [Watch System Startup & GPS Fix Test on YouTube](https://youtu.be/SuNiSawtJ5U)

---

### Author & Team
Hardware & Electronics Design by **Francesco Miletto** for **Sapienza Foiling Team (SuMoth Challenge)**.
