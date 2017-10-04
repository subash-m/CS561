# Activity Recognition for Energy Efficiency in Workplace

## Abstract
 - Detection of human activities is a set of techniques that can be used in wide range of applications, including smart homes and healthcare.
 - In Activity recognition, we need to correctly identify and recognize the individual’s current activities.
 - Designed an IoT device to monitor the activities of the user, without breaching the privacy of the user.
 - Implemented <b>KNN Algorithm</b> to learn the pattern in the sensor data, which has been used to recognize the user activity.
 
## Architecture and IoT setup

 - The IoT device is placed in the Robotics Lab in Dept. of Computer Science at IIT Guwahati.
 - The IoT device is fitted with PIR, PING and LIGHT sensor. All these sensors gave us different sensor values of the student's activities performed in the lab.

| <img src="/Images/Pi Setup.jpg" width="250px" alt="IoT">  | <img src="/Images/Arch.PNG" width="622px" alt="System Architecture for the test bed"> |
|:---:|:---:|
| IoT device setup | System Architecture for the test bed |

## Activity Classes
The following four classes have been identified suitable for the problem.
1) Sitting + Screen ON
2) Idle + Screen ON
3) Sitting + Screen OFF
4) Idle + Screen OFF

## Data

 - The data has been collected for 24 hours each day and it has been manually annotated.
 - The following is the snapshot of the readings from LIGHT, PING and PIR sensor, during the beginning of SITTING activity.

| <img src="/Images/data.PNG" width="436px" alt="Data recorded from IoT">  | <img src="/Images/norm.PNG" width="436px" alt="Normalized data"> |
|:---:|:---:|
| Data recorded from IoT - Annotated | Normalized data |

## Sensor Readings and Activity Patterns

