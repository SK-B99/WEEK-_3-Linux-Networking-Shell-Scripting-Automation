# DAY 5 – Networking + Scripting Final Lab

## Topics: 
Combining CLI networking tools with automation

## Demo: 
Build a simple monitoring script for uptime or endpoint status

The `uptime` command in Linux tells how long the system has been running. It gives a one-line display of the following information: the current time, how long the system has been running, how many users are currently logged on, and the system load averages for the past 1, 5, and 15 minutes.

In Linux networking, an **endpoint** is defined as any device operating the Linux OS that establishes a connection to a network. This category encompasses a wide range of devices, such as servers, desktop computers, laptops, and Internet of Things (IoT) devices.

The demo is shown in Figure 16.

![Figure 16](https://github.com/user-attachments/assets/6e5c5d35-3398-4d62-a729-0eae1add9742)

It was automated as seen in Figure 19.

![Figure 19](https://github.com/user-attachments/assets/fe5ba444-9889-436d-823a-78e58b99f17e)

### Final Lab Task
Write a Bash script that:
- Pings a list of predefined servers
- Logs their online/offline status with timestamps
- Sends results to a log file
- Runs automatically via cron

![Figure - Script Example](https://github.com/user-attachments/assets/ebc7120e-d337-4611-83da-33da823afef7)

![Figure - Cron Execution/Output](https://github.com/user-attachments/assets/d00acfec-dd67-46ae-8e7b-48c9ca396d5f)
