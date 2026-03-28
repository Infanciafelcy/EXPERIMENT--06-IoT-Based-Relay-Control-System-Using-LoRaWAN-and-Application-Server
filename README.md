# EXPERIMENT--06-IoT-Based-Relay-Control-System-Using-LoRaWAN-and-Application-Server
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
<img width="1882" height="1093" alt="Screenshot 2026-03-18 153842" src="https://github.com/user-attachments/assets/36e6c993-8893-49be-99e3-e55e93c3b3c1" />

### 2. Network Server – Recent Events
<img width="1913" height="1053" alt="Screenshot 2026-03-18 154056" src="https://github.com/user-attachments/assets/4b0b44ea-619b-4269-8e7b-59f189699591" />

<img width="1892" height="984" alt="Screenshot 2026-03-18 154230" src="https://github.com/user-attachments/assets/d94d1cfa-e6a9-4d71-8b13-b845f1768a80" />


### 3. Dashboard Command Sending
<img width="819" height="311" alt="image" src="https://github.com/user-attachments/assets/37355103-2c15-48e3-9ddb-e5f683905d0d" />


### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON 
<img width="1903" height="1059" alt="Screenshot 2026-03-18 154204" src="https://github.com/user-attachments/assets/4f6e4bf1-344d-4114-a576-8c063c518f37" />

### Bulb OFF → Relay OFF
<img width="1916" height="1085" alt="Screenshot 2026-03-18 153334" src="https://github.com/user-attachments/assets/f059aa71-fece-4060-bb57-61e1d62bcf55" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
