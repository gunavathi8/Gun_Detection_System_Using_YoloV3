# Gun_Detection_System_Using_YoloV3

## Problem Statement
- Gun detection in public spaces is critical, as individuals carrying guns are indicators of potential danger.
- Acts of gun violence have led to numerous casualties due to:
   - Terrorist attacks
   - Mentally disturbed individuals
   - Influence of online games or societal factors
- Rapid law enforcement response plays a significant role in minimizing victims during such incidents.

## Need for Automated Surveillance
- Manual monitoring of surveillance cameras is prone to human errors.
- There is a growing need for automated visual surveillance systems to enhance security and reduce reliance on manual observation.
- The system aims to send real-time alerts when handguns are detected, enabling timely responses.

## Proposed Solution
- Developed a gun detection system based on the YOLOv3 algorithm.
- The system:
   - Detects handguns in real-time using surveillance cameras.
   - Sends an alert message to supervisors or law enforcement when a gun is detected.
   - Reduces the risk of false alarms by fine-tuning the detection process.

## Key Features of the System
- Custom Dataset Creation:
   - Created a custom dataset of handgun images from all possible angles.
   - Merged the custom dataset with an existing dataset to increase accuracy.
- YOLOv3 Algorithm:
  - The merged dataset is trained using the YOLOv3 algorithm for accurate handgun detection.
- Real-Time Notifications:
   - Integrates with a Raspberry Pi to send real-time location alerts.
   - Alerts are sent to:
       - Nearby police stations
       - Security officials of the affected building/area.
    
## Goals of the Detection System
- Accurately identify handguns without triggering false alarms for similar objects.
- Improve response times of law enforcement agencies to potential threats.
- Provide an efficient, automated, and reliable gun detection mechanism for enhanced public security.
