# Hardware

## Connect the Ultrasonic Sensor to ESP32:
- Connect the VCC pin of the Ultrasonic Sensor to the 5V pin on the ESP32.
- Connect the GND pin of the Ultrasonic Sensor to the GND pin on the ESP32.
- Connect the Trig pin of the Ultrasonic Sensor to a GPIO pin on the ESP32 (e.g., GPIO2).
- Connect the Echo pin of the Ultrasonic Sensor to another GPIO pin on the ESP32 (e.g., GPIO4).

# Software

## Set up Firebase:

- Create a new Firebase project and set up a Realtime Database.
- Note down the Firebase project credentials (API Key, Database URL, etc.).

## Set up Arduino IDE:

- Install the ESP32 board support package in your Arduino IDE. You can find instructions on how to do this on the official GitHub repository.

## Install Required Libraries:

- You'll need the Firebase ESP32 library to communicate with Firebase. Install it using the Library Manager in Arduino IDE.
  
## Write the Arduino Code:

- go to main.cpp file and upload to Arduino IDE.

## Create the MIT App:

- You can create the MIT App using MIT App Inventor. It's a simple web-based platform for creating Android apps. There are many tutorials available online on how to create a basic app to display Firebase data.

## Connect MIT App to Firebase:

- Use the Firebase component in MIT App Inventor to connect to your Firebase project and retrieve the distance data.

## Test:

- Deploy your app on an Android device and run the ESP32. You should be able to see the distance data from the Ultrasonic Sensor in your app.

## Reminder

- Remember to replace the placeholders (e.g., YOUR_FIREBASE_HOST, YOUR_FIREBASE_AUTH, YOUR_WIFI_SSID, YOUR_WIFI_PASSWORD) with your actual credentials.

- This is a basic example to get you started. Depending on your specific requirements, you may need to modify and expand upon this code.


  
