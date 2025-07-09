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
