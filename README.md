# Cameră Climatică PLC

## Prezentare Generală
Proiectul implică utilizarea a două aplicații SCADA și un PLC Siemens S7-1214 pentru monitorizarea și controlul temperaturii din interiorul unei camere climatice, construită dintr-un frigider modificat și un încălzitor PTC. Sistemul asigură o reglare precisă a temperaturii pentru diverse aplicații, oferind date în timp real și control prin interfețe SCADA ușor de utilizat.

## Componente Software
- **Soft Converter Temp:** Utilitar pentru conversia datelor de temperatură din valoarea de rezistență PT100 și afișarea temperaturii în grade Celsius.
- **Soft Ignition:** Software SCADA pentru vizualizarea proceselor; necesită autentificare cu utilizator: `user` și parolă: `password`.
- **Soft OPC UA KepServerEx:** Server OPC UA configurat care recuperează datele prin Modbus de la PLC.
- **Soft Simple SCADA:** Software SCADA simplu pentru vizualizarea proceselor; installer-ul software este atașat.
- **Soft TIA v18:** Program creat pentru PLC pentru control; necesită Siemens TIA Portal v18.

## Autentificare
Pentru accesarea software-ului SCADA Ignition:
- **Utilizator:** user
- **Parolă:** password

---

# Climatic Chamber PLC

## Overview
This project involves using two SCADA applications and a Siemens S7-1214 PLC to monitor and control the temperature inside a climate chamber, built from a modified refrigerator and a PTC heater. The system ensures precise temperature regulation for various applications, providing real-time data and control through user-friendly SCADA interfaces.

## Software Components
- **Soft Converter Temp:** Utility for converting temperature data from PT100 resistance value and displaying temperature in Celsius.
- **Soft Ignition:** Ignition SCADA software for process visualization; requires authentication with user: `user` and password: `password`.
- **Soft OPC UA KepServerEx:** Configured OPC UA server that retrieves data via Modbus from the PLC.
- **Soft Simple SCADA:** Simple SCADA software for process visualization; the software installer is attached.
- **Soft TIA v18:** Program created for the PLC for control; requires Siemens TIA Portal v18.

## Authentication
For accessing the Ignition SCADA software:
- **Username:** user
- **Password:** password

