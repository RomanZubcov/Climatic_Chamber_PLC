# Climatic_Chamber_PLC
The project involves using two SCADA applications and a Siemens S7-1214 PLC to monitor and control the temperature inside a climate chamber, built from a modified refrigerator and a PTC heater. The system ensures precise temperature regulation for various applications, providing real-time data and control through user-friendly SCADA interfaces.

Software Components
The following software components are used in this project:

Soft Converter Temp: Utility for converting temperature data from PT100 resistance value and displaying temperature in Celsius.
Soft Ignition: Ignition SCADA software for process visualization; requires authentication with user: user and password: password.
Soft OPC UA KepServerEx: Configured OPC UA server that retrieves data via Modbus from the PLC.
Soft Simple SCADA: Simple SCADA software for process visualization; the software installer is attached.
Soft TIA v18: Program created for the PLC for control; requires Siemens TIA Portal v18.
