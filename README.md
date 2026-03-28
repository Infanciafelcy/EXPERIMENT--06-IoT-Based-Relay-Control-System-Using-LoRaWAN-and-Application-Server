# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server

### NAME : INFANCIA FELCY P
### REG NO: 212223040067
### DATE : 09/03/2026
## Aim
To configure a LoRaWAN end device and monitor IR sensor data using a network server and dashboard visualization.

## Components Required
- LoRaWAN End Device-STM32
- LoRaWAN Gateway
- Application Server Dashboard
- Serial Port Utility
- Development Tools (STM32CubeIDE, STM32CubeProgrammer)

## Procedure
1. Open STM32CubeIDE and import the project from the realy-control project directory.
2. Select the LoRaWAN End Node project for the NUCLEO-WLE5JC board.
3. Clean all previous build files using the Clean Project option in the build configuration.
4. Build the project to generate the firmware files.
5. Flash the compiled firmware into the STM32 board using STM32CubeProgrammer with baud rate set to 9600.
6. Open the network server console and login using your registered email ID and password.
7. Register the device by selecting Device Types and adding the LoRaWAN device in the network server.
8. Open the Serial Port Utility  give the AT commands and verify device connection through the serial port utility
9. Create a dashboard on the application server by clicking the Add Dashboard option.
10. Add widgets and commands to visualize the relay status data.
11. Send control commands from the dashboard to control the relay.

## Output
### 1. Serial Port Utility – Network Server Connection
<img width="1364" height="713" alt="image" src="https://github.com/user-attachments/assets/5a41bf1f-faff-4f95-8d5a-8fc3c4a1396f" />
<img width="1364" height="716" alt="image" src="https://github.com/user-attachments/assets/2cff4e65-a275-4273-9cfc-bfdde29fcbf9" />

### 2. Network Server – Recent Events
<img width="1350" height="637" alt="image" src="https://github.com/user-attachments/assets/dc795d92-fa9d-4866-ad78-abccd88da4c7" />
<img width="1362" height="679" alt="image" src="https://github.com/user-attachments/assets/bb5f426c-edf2-480f-8f30-38716490fd90" />

### 3. Dashboard Command Sending
<img width="1356" height="638" alt="image" src="https://github.com/user-attachments/assets/65226f74-21ad-4325-8cdb-407d4b485b8b" />
<img width="1360" height="677" alt="image" src="https://github.com/user-attachments/assets/d6488885-96af-4357-85ec-fc84968219d2" />

### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="1280" height="570" alt="image" src="https://github.com/user-attachments/assets/68a7225b-5d4a-44c4-8b6f-4becb2c06ebe" />

### Bulb OFF → Relay OFF
<img width="570" height="1280" alt="image" src="https://github.com/user-attachments/assets/e35bdff3-3a44-4e42-a82b-95ec10dc16e5" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
