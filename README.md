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
<img width="731" height="454" alt="image" src="https://github.com/user-attachments/assets/31d11a26-b6d0-4ad2-a62c-5a849de01c1c" />

### 2. Network Server – Recent Events
<img width="712" height="409" alt="image" src="https://github.com/user-attachments/assets/06944a8f-393a-41ca-a348-f489ee0839a9" />

### 3. Dashboard Command Sending
<img width="732" height="377" alt="image" src="https://github.com/user-attachments/assets/9cfea628-6c0c-4a74-8fed-c351b42f93a8" />

### 4. Relay Status Dashboard Output
<img width="733" height="441" alt="image" src="https://github.com/user-attachments/assets/7f6d9e6b-275a-4487-ae51-4f01d55de30c" />


<img width="733" height="438" alt="image" src="https://github.com/user-attachments/assets/3c3a1601-7a1d-4d2e-879b-736f14c4a3a7" />


<img width="721" height="447" alt="image" src="https://github.com/user-attachments/assets/5c30d6dc-7779-4f4a-a665-2d2d9f43301b" />


<img width="720" height="435" alt="image" src="https://github.com/user-attachments/assets/08bd572b-918f-429a-998a-f53a4f1b60ec" />

<img width="735" height="441" alt="image" src="https://github.com/user-attachments/assets/d0235462-023b-41ec-a29f-ff1fe6d471dd" />

### Bulb ON → Relay ON  
<img width="732" height="394" alt="image" src="https://github.com/user-attachments/assets/6b7dfedb-92a1-4515-a4c5-920d0c5161d3" />

### Bulb OFF → Relay OFF

<img width="724" height="419" alt="image" src="https://github.com/user-attachments/assets/c08b35ff-56eb-48bb-ba6e-7f9b5654a45f" />

## Conclusion
The experiment demonstrates successful relay monitoring and control using LoRaWAN communication with real-time visualization on the dashboard.
