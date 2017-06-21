# Raspberry Pi Smart Camera

This project is an ongoing work under Anusua Trivedi, Data Scientist Sr. at Microsoft. Anusua is a mentor to Isha Chakraborty & Neelagreev Griddalur, who are the main contributors to this project.

The Raspberry Pi Smart Camera is a platform that allows one to perform object recognition using a Raspberry Pi. This software implements the Microsoft Computer Vision API and the Microsoft Bing Speech API. 

For more information on Microsoft Computer Vision APIs and the Microsoft Bing Speech APIs, see the Microsoft Computer Vision API Documentation and Microsoft Bing Speech APIs on docs.microsoft.com. 

Inspiration for this project came from Charles Channon’s article at https://www.hackster.io/cchannon/raspberry-pi-smart-camera-a8c786.

If you run into any problems, feel free to contact Isha Chakraborty at ishachak@gmail.com or Neelagreev Griddalur at neelagreev@griddalur.xyz

LinkedIns: 

https://www.linkedin.com/in/ishachakraborty/

https://www.linkedin.com/in/neelagreevgriddalur/



# Source Code

Clone the sources: git clone https://github.com/Pi-Smart-Camera

# The Project
This is a Python application to demonstrate the uses and integrations of the Computer Vision APIs and Bing Speech APIs. 

# Dependencies
This repository contains all of the necessary files and dependencies excluding Python needed to build this project and use it yourself. A drone is needed for recreating this project, a Parrot AR Drone 2.0 Power Edition Quadricopter is recommended for best compatibility. 

Run “pip install git+https://github.com/westparkcom/Python-Bing-TTS.git”

Install ffmpeg 


# Running the Project 

Run the command, “./start.sh” to run the shell file and follow the instructions present on your terminal window by entering the credentials of your desired network and reconnect to it after completion. 

Open a second terminal window In the window, run “./object_detect.sh” to take the picture. This will run the ComputerVision.py file to identify the object. 





