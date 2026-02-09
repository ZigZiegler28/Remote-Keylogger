# Remote-Keylogger
## Summary
Create a remote keylogger in Python that is disguised as a photo. After the photo, it opens, takes a screenshot of the user's computer screen, takes a picture using the user's camera, and sends both images to a Discord Server, the keylogger will run for 30 mins.

## Python Code
### External Libraries
- from pynput import keyboard: Reading keyboard inputs
- import pyautogui: Taking screenshots
- import cv2: Access the users webcam
- import requests: Used to make HTTP Requests, used to send data to Discord.
- import os: Access operating system functions.
- import time: Control the length for how long the keylogger would run.
- import shutil: Used to copy files and moving it into a folder

### Configuration
<img width="1068" height="78" alt="Screenshot 2025-11-27 195717" src="https://github.com/user-attachments/assets/735fa6de-789f-455c-8405-7671ebe404ba" />
<img width="1836" height="816" alt="Screenshot 2025-11-27 195756" src="https://github.com/user-attachments/assets/77c10d94-d9c1-4cbb-8faf-63431c1bebba" />
<img width="1440" height="886" alt="Screenshot 2025-11-27 195900" src="https://github.com/user-attachments/assets/9ec61125-b802-42d4-93f7-ee3fbb34a4d1" />
- Creating a Discord server where all the media will be sent to.

### Keystroke Logger Function
<img width="1389" height="608" alt="Screenshot 2025-11-27 203739" src="https://github.com/user-attachments/assets/c771c09a-28db-44d1-9e6f-2e78cf5a6b7d" />
- Makes the code run each time a key is pressed and records the key in a text file.

### Screen and Webcam Capture Function
<img width="1403" height="612" alt="image" src="https://github.com/user-attachments/assets/4f0be4e5-e9f2-49cd-a6f5-dcc2783a34f0" />
- Captutes a screenshot and takes a picture using the users webcam and save the file.

### Transmition
<img width="1396" height="618" alt="image" src="https://github.com/user-attachments/assets/07d7e3f6-f169-4ff0-9c37-da23e06a0a4c" />
- Sends all the media to Discord Server using webhock

### Removing Evidence
<img width="1398" height="618" alt="image" src="https://github.com/user-attachments/assets/bced2d4b-767e-42c0-92a3-d220ba9dbe67" />
- After keylog is successful it will delete all the screenshots and evidence.

## Executable compile
The python program can be compiled into a standalone executable through the commandline using PyInstaller. If we save the python file as a ".pyw" extension, the program will run in a mode "without console", meaning that it will run without popping up command prompts or new windows. This will help to stay undetected.
<img width="1400" height="611" alt="image" src="https://github.com/user-attachments/assets/0fcc245a-57ed-4745-9a35-e576c4c39ddc" />

## WinRAR packaging
Using WinRAR we can package the files to be an SFX archive. The program will now be embedded into a photo, and when the photo is opened it will execute the keylogger under the radar. We can disguise the icon and the opening of the file, but cannot get the file type to change from "Application".
<img width="1413" height="646" alt="Screenshot 2025-11-27 203552" src="https://github.com/user-attachments/assets/c11eac83-cbf7-4eef-b9dc-e14ff2915fb8" />
<img width="1407" height="630" alt="Screenshot 2025-11-27 203616" src="https://github.com/user-attachments/assets/f92e521a-c1f3-4044-8306-279bb5076e13" />
<img width="1029" height="653" alt="image" src="https://github.com/user-attachments/assets/12350caa-1788-45cc-8fbf-0eb8f4534396" />

## Demo 
<img width="1830" height="829" alt="image" src="https://github.com/user-attachments/assets/20abdf89-344a-4c32-8fad-9e50f780fbb8" />









