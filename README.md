# MOBILE DETECTOR FOR THE CLASSROOM MONITORING 

This repository contains the implementation of a mobile detector system that can identify when students are using their phones in class. This system aims to enhance classroom discipline and ensure an undistracted learning environment. The detector will use a combination of hardware and software solutions to accurately identify mobile phone usage and alert the instructor.


---

## 🎯 **Key components**

The solution is using the esp32s2 to dectect phones and seng email towards the teachers
Using the ESP32-S3 (or ESP32-S2) to detect mobile phones and send email notifications to teachers is a practical and efficient solution for enforcing campus rules. Here's a comprehensive guide to achieving this:

Steps to Implement Mobile Phone Detection with Email Notifications:
Hardware Setup:

Use the ESP32-S3 module.

Connect a suitable sensor (e.g., a camera module or RF detector) to detect mobile phones.

Install Necessary Libraries:

Install libraries for Wi-Fi, email, and sensors (e.g., camera).

Configure Wi-Fi and Email Settings:

Set up your Wi-Fi credentials and SMTP email settings.

Write Code for Mobile Phone Detection and Email Notification:

Combine the mobile phone detection logic with the email notification feature



---

##  **How It Works:**

Capture: The camera captures a continuous video feed of the user's hand gestures.
Preprocess: The video frames are processed to isolate the hand and remove the background.
Recognition: The processed images are fed into a trained machine learning model that classifies the hand gesture.
Translation: The recognized gesture is translated into corresponding text or speech

---

## *Instalation:**

Install the ESP32S2 board in your Arduino IDE, follow these steps:

Step-by-Step Guide
1. Open Arduino IDE
Launch the Arduino IDE on your computer.

2. Add Board Manager URL
Go to File > Preferences.

In the "Additional Board Manager URLs" field, add the following URL:

https://raw.githubusercontent.com/espressif/arduino-esp32/gh-pages/package_esp32_index.json
Click OK to save the changes.

3. Install ESP32 Board
Go to Tools > Board > Boards Manager.

Search for "ESP32".

Find the "ESP32 by Espressif Systems" package and click Install.

Wait for the installation to complete.

4. Select ESP32 Board
Go to Tools > Board and select "ESP32S2" from the list.

5. Install Necessary Libraries
You may need to install additional libraries depending on your project requirements. For example, if you're using the ESP32 camera, you can install the ESP32 Camera library by going to Sketch > Include Library > Manage Libraries and searching for "ESP32 Camera".

6. Connect Your ESP32S2 Board
Connect your ESP32S2 board to your computer using a USB cable.

7. Upload Your Sketch
