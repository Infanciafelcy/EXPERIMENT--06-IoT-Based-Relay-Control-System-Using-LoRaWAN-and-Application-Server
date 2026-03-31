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

#### AT+FDR
![Uploading image.png…]()


#### AT+NJM=2
<img width="1600" height="957" alt="image" src="https://github.com/user-attachments/assets/f1fb624e-1359-49ed-a44e-a43160d016a8" />

#### AT+ADR=1
<img width="1600" height="949" alt="image" src="https://github.com/user-attachments/assets/009810cf-701d-43b0-bcf5-261eb070b433" />

#### AT+TDC=600000
<img width="1600" height="950" alt="image" src="https://github.com/user-attachments/assets/39e97888-b2f6-433f-b130-387cfad910a3" />

#### AT+CLASS=C
<img width="1600" height="922" alt="image" src="https://github.com/user-attachments/assets/f038d699-7282-4d9c-aea6-345e92bacf16" />

#### AT+DEUI=
<img width="1600" height="947" alt="image" src="https://github.com/user-attachments/assets/f0da42fa-ffe9-4f8e-9687-9c46d6dab020" />

#### AT+APPEUI=
<img width="1600" height="945" alt="image" src="https://github.com/user-attachments/assets/06b91bd7-1b5e-4d36-b2ca-b33eba39c273" />

### AT+APPKEY=
<img width="1600" height="946" alt="image" src="https://github.com/user-attachments/assets/2f8b63e3-1fdc-4687-a1ec-dbe98b5fae4e" />



#### ATZ
<img width="1600" height="927" alt="image" src="https://github.com/user-attachments/assets/8b95ff4f-5d42-42c8-ac71-2f3a95079a11" />

### 2. Network Server – Recent Events
<img width="1600" height="868" alt="image" src="https://github.com/user-attachments/assets/9fb42b9c-4129-4de3-b57c-a4a8ee1c6897" />

### 3. Dashboard Command Sending
<img width="1600" height="847" alt="image" src="https://github.com/user-attachments/assets/469d6dee-9f84-447b-a9f0-21fe157d659e" />
<img width="1536" height="1024" alt="image" src="https://github.com/user-attachments/assets/7a52c3ff-48b2-4f78-b084-462199f4deb3" />



### 4. Relay Status Dashboard Output

### Bulb ON → Relay ON  
<img width="570" height="473" alt="image" src="https://github.com/user-attachments/assets/8c851cae-529a-4809-ba89-6d81eaa94ca3" />


### Bulb OFF → Relay OFF
<img width="752" height="570" alt="image" src="https://github.com/user-attachments/assets/7f8f0f57-550f-4d8d-8584-f48ce82ff060" />


## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
