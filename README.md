# Home Alarm Automation System using Arduino (TinkerCad)

The **Home Alarm Automation System** is a security project built using **Arduino** on **TinkerCad**. This system utilizes sensors to detect motion and triggers an alarm to notify homeowners of potential intrusions. It is designed to provide an affordable and efficient home security solution using easily accessible electronic components.

##  List of Components Used
- Arduino Uno
- Breadboard
- LCD (Liquid Crystal Display)
- PIR Motion Sensor
- Light Bulb
- Potentiometer
- Temperature Sensor (TMP36)
- Photoresistor (LDR)
- USB Cable


## Circuit Diagram or TinkerCad Link
This is our Circuit Diagram

![image](https://github.com/user-attachments/assets/5870409c-977f-4e7f-9ad0-94327cb46893)


## How the System Works (Step-by-step Explanation)
Output:
1) No movement.
![image](https://scontent-mnl3-1.xx.fbcdn.net/v/t1.15752-9/483923167_1824635625046613_848285924999795230_n.png?_nc_cat=103&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeFU3C9TtTmlchA5qMzairb_PwVTGZm_fvI_BVMZmb9-8rqOl-yKKK6voAXc6XdwuQKcP8iWsGT0GX5FXu_gwaJh&_nc_ohc=UlbwGFtPvM4Q7kNvgEb_psx&_nc_oc=AdnKfq__tYELpwOgaW-wuCqRxiZCAlwqgOQjAAamrkaRybykCV50ES7yvykMalogv5Y&_nc_zt=23&_nc_ht=scontent-mnl3-1.xx&oh=03_Q7cD1wFta8JLIw48eezw58gr4hI6VdTO6GitpFkK2bYsGqQK4A&oe=68108A61)

2) if there is movement.
![image](https://scontent-mnl1-1.xx.fbcdn.net/v/t1.15752-9/483088742_656602757311755_3818135389740780242_n.png?_nc_cat=110&ccb=1-7&_nc_sid=9f807c&_nc_eui2=AeEgJGXih3z1ZXrJS6Qq1iS0ZtzQWLCTooJm3NBYsJOignW7OfKCM25GofVDjO0QH8mkrWDDCyQK9iEtGCUM1bFJ&_nc_ohc=tYbKTSwAkksQ7kNvgHxW6vy&_nc_oc=AdmM7SvirlFAHwPCooNm4Ooh2DIxJNVOSZWYCZlA2NbayiFk_YM4m6PD6xfi4g6IMK0&_nc_zt=23&_nc_ht=scontent-mnl1-1.xx&oh=03_Q7cD1wGAwiNBlsaK7Q-ewH7faoVglY0dap8mph7lHOHbIaXMnQ&oe=68105FD1)

3) detected movement with light bulb and fan ON.
![image](https://github.com/user-attachments/assets/5ef39425-a8dc-40a3-9660-8acff70b6acf)

## How to Run the Arduino Code

1) Install the Arduino IDE: Download and install the Arduino IDE from the official Arduino website.

2) Connect the Arduino Board: Use a USB cable to connect your Arduino board to your computer.

3) Select the Board and Port: In the Arduino IDE, go to Tools > Board and select the correct board type (e.g., Arduino Uno). Then, go to Tools > Port and select the appropriate port.

4) Open or Write the Code: Either write your Arduino code or open an existing .ino file.

5) Verify and Upload: Click the ✔ (Check) button to verify the code for errors, then click the → (Upload) button to upload it to the Arduino board.

6) Monitor the Output (Optional): Open the Serial Monitor (Tools > Serial Monitor) to view any real-time data output.

## Possible Enhancements or Future Improvements

1) Wireless Connectivity: Add a Wi-Fi or Bluetooth module for remote monitoring and control.

2) Sensor Calibration: Improve sensor accuracy by implementing calibration routines.

3) Data Logging: Integrate an SD card module or cloud service for storing sensor readings.

4) Mobile App Integration: Develop a companion mobile app for real-time monitoring and control.

5) Energy Efficiency: Optimize power consumption using low-power modes or alternative power sources like solar panels.

6) AI Integration: Use machine learning to analyze sensor data and make intelligent decisions.
