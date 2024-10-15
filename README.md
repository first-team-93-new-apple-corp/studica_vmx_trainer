# Studica Robotics VMX FRC Training Robot Documentation

## Introduction
Team 93's documentation and code for the [Studica Robotics VMX FRC Training Robot](https://www.studica.com/studica-robotics-brand/vmfrc-compatible-training-bot). This robot is powered by a Studica Robotics VMX Robotics Controller which uses a Rasberry Pi model 4B in combination with a navX-IMU to emulate the capabilities of a [NI Roborio](https://www.andymark.com/products/ni-roborio-2). I referenced the [Official Documentation](https://docs.wsr.studica.com/en/latest/index.html) to help me set up this robot.

## Software Installation
In order to use this robot, you need to do some additional setup as this only works with certain versions of WPILib and FRC Game Tools. You can use 2024 FRC Game Tools with this, but it is reccommended you use 2020 FRC Game Tools because the robot only works with 2020 WPILib libraries.

### WPILib & Visual Studio Code

#### Source 1: Studica Link
Studica provided a link to a Sharepoint folder for all the software needed to be downloaded. If you choose to download all the folders and CAD models the download is ~6 GB 
[Link](https://studicalimited.sharepoint.com/sites/SR-Resources/Shared%20Documents/Forms/AllItems.aspx?viewid=594b16af%2De465%2D418c%2D8993%2D7bd203109209)

#### Source 2: Team 93 Members Only
In the team Google Drive, under ```Engineering > Software > Studica Robot Files``` there is the download as a backup.

Once you have downloaded the files, extract the zip file to your desktop or somewhere you can remember. Run the WPILib installer for your OS and version (Most likely Windows 64 bit, but you can easily check in Settings > System > About). You will have to select whether you want to install for just your user or all users, but after that you should be presented with a screen that asks you to select how you want to install VS Code. Select Existing Download and use the offline VS Code installer provided in the download. It should install and you will now have 2020 WPILib and VS Code installed.