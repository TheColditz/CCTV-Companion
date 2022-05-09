

# CCTV-Companion
A Python3 based Tool to help in CCTV related work
(Work in Progress!)

## Table of contents
* [General info](#general-info)
* [Current Features](#current-features)

## General info

CCTV-Companion is a Python-Script that aims to help in both planning, setting up and doing maintenance on your Dahua Technology Equipment.

![image](https://user-images.githubusercontent.com/79027579/167003822-10998845-1840-4420-9ab8-802695f75ffd.png)


Windows .exe File: (05. May 2022, 10:16 AM)
https://www.dropbox.com/s/1rbebdu6feqkbt7/CCTV%20Companion%20v0.1.exe?raw=1

## Current Features

- typing "webcam" in the IP-Address field will open the first recording device. (if SMD is checked, Object Detection will run on it)
- typing "imgsrc=" followed by the path to an image will open the image (if SMD is checked, Object Detection will run on it)


- Object Detection using a pre-trained tensorflow model. This can be toggled ON/OFF.
- Outputting Serial No., Model Name and Firmware Version of Device
- Opening a Live View (RTSP Stream) with the ability to control a PTZ Camera (Up, Down, Left, Right, Zoom In/Out, Focus, Wiper On/Off)
- Copying a usable RTSP-Link to your Clipboard so it can easily be shared or pasted into other programs like VLC.
- Opening the Web Interface of specified device
- Rebooting Device
- Grabbing a Snapshot and displaying it
- Saving a Diagnostics File (grabs some of the more important settings and infos on the device and saves them in a .txt)
- Factory Resetting a device and switching all settings to default value
- Capacity Calculation (Counting # of cameras using specified codec and calculating expected bandwidth. Data gathered from Dahua Techs. Security Calculator)
