TechOS Version 0.0.3 - README
Introduction

Welcome to TechOS Version 0.0.3! This lightweight command-line operating system simulation is designed for educational and entertainment purposes. You can perform various tasks such as system information retrieval, calculations, viewing the clock, and even saving your data. The program is straightforward and easy to use.
Table of Contents

    Getting Started
    Features
    How to Use
    Saving and Loading Data
    Updating TechOS
    Known Bugs
    Terms of Service
    License Agreement

1. Getting Started
System Requirements

    Windows Operating System
    A working command prompt (cmd)
    Basic knowledge of batch scripting (optional)

Installation

Important: You must extract the entire OperatingSystem folder to your desktop. Do not extract the contents individually—extract the whole folder to ensure the correct file paths.

    Download and extract the contents of the TechOS package.
    Place the entire OperatingSystem folder on your desktop.
    Ensure that the folder structure looks like this:

scss

[Your user directory]\Desktop\OperatingSystem\
   ├── SystemFiles\
   │   └── SaveData\
   │       └── data.sf
   └── OS_V0.0.3.bat (or similar batch files for newer versions)

    Double-click the OS_V0.0.3.bat file inside the OperatingSystem folder to start TechOS.

2. Features

    System Information: Retrieve basic system specs.
    Calculator: Perform basic arithmetic operations.
    Clock: View the current time and date.
    Save Data: Save your name into a file for later use.
    Update Checker: Automatically detect and apply updates to TechOS.

3. How to Use

    Starting TechOS: Double-click OS_V0.0.3.bat inside the OperatingSystem folder on your desktop to start the system.

    Enter Your Name: Upon startup, the system will ask for your name. Enter your name and proceed.

    Main Menu: You'll be presented with several options:
        1. System Info
        2. Calculator
        3. Clock
        4. Songs
        5. Antivirus
        6. Check For Update
        7. Save data

    Type the number corresponding to your choice and press Enter.

    Performing Operations: Follow the prompts for each task. For example, choose 2 for Calculator and perform operations as instructed.

    Returning to Menu: After completing any task, you will be returned to the main menu.

4. Saving and Loading Data

    Saving Your Name: To save your name, choose option 7. Save data from the main menu. Your name will be saved to [Your user directory]\Desktop\OperatingSystem\SystemFiles\SaveData\data.sf in the format name:[username].
    Loading Data: Currently, there is no automatic data loading feature. However, you can view your saved data by opening the data.sf file with a text editor.

5. Updating TechOS

    Check for Updates: Select option 6. Check For Update from the main menu. The system will check for any new versions in the [Your user directory]\Desktop\OperatingSystem\ directory.
    Automatic Update: If a new version is detected (e.g., OS_V0.0.4.bat), TechOS will automatically close and start the newer version.

6. Known Bugs

Please be aware of the following known issues in TechOS Version 0.0.3:

    Updates May Not Work Properly: The update feature may not always detect or properly launch the latest version of the OS.
    Songs and Antivirus: The Songs and Antivirus options are not fully scripted. Attempting to use these features will crash the OS.
    No Load Feature: Although there is a save feature, there is currently no option to load saved data when starting the OS.
    Limited Save Functionality: The save feature currently only saves your username. No other data is saved at this time.

These issues are known and will be addressed in future updates. Thank you for your understanding.
7. Terms of Service

By using TechOS, you agree to the following terms:

    Use at Your Own Risk: TechOS is provided "as is," without warranty of any kind, express or implied. The user assumes all risks associated with the use of this software.

    Personal Use: This software is intended for personal, non-commercial use. Any commercial use is strictly prohibited without explicit permission from the author.

    Data Storage: TechOS stores user data in plain text format. The user is responsible for the security and privacy of their data.

    Modification: Users may modify the script for personal use. Redistribution of modified versions is prohibited.

    Termination: Violation of these terms may result in the termination of your access to future updates or support for TechOS.

8. License Agreement

TechOS Version 0.0.3 is licensed under the MIT License. By using this software, you agree to the terms of the license as outlined below:

sql

MIT License

Copyright (c) 2024 ZachStudios

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Thank you for using TechOS Version 0.0.3. If you have any questions or need support, please contact ZachStudios.

Contact Info
Discord: zachisbisexual
Email:techeyboyyt@gmail.com