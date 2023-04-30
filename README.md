# SWE4740-Embedded-Software-Development-Smart-Health-Tracker
A smart health tracker for real time observation of human health that provides human health
suggestions based on the user's current vitals.
Our health tracker can measure body temperature, SpO2 (also known as oxygen saturation of the body), pulse rate, and blood pressure of a user. It can provide the current state of temperature and humidity of the environment. It can calculate a person's footstep counts which represents calorie burn of the user and can count total sitting time to allow users to take a break now and then.


Project Description:
____________________

We want to build a smart health tracker which will monitor the user's basic health condition
and accordingly will provide suggestions . Our project has several things to focus on. The
key features of our project are:

● Measure Body temperature of user
● Measure SpO2, also known as oxygen saturation of body
(Oxygen saturation (SpO2) is a measurement of how much oxygen your blood is
carrying as a percentage of the maximum it could carry)
● Measure Heart rate of user.
● Measure Blood Pressure of the user.
● Collect Footstep/calorie burn of the user.
● Provides the current state of the humidity of the environment.
● Provides the current state of the temperature of the environment.
● Calculates a person's sitting time to avoid chronic pain and allow users to take a break
now and then.


Using the temperature sensor, we can detect drastic changes in the body temperature, detect anomalies. With the heart beat sensor, we can get historical data of the user’s heart condition. Accelerometer can keep track of the amount of calories burnt in a specific time. The Pulse Oximeter and Heart rate sensor will keep track of the Heart rate and Oxygen saturation of the user’s body, which is very important during the COVID 19 pandemic. We can immediately be
alerted in cases where a patient’s oxygen rate is decreasing and take steps accordingly. The pressure monitor for sitting will keep track of how many hours we are spending at a time sitting, and help reduce effects of chronic back and shoulder pain, a problem that is very frequent in our current lifestyle. The DHT11 sensor to measure environment temperature & humidity will give us real time data on the weather, to notify whether users can take exercise or not and allowing us to prevent cases like heat stroke, dehydration etc.

Necessary Sensors:
__________________
● MAX30205: Temperature sensor to measure body temperature of a user.
● HeartBeat sensor module: A sensor to measure heart beat of a user.
● ADXL 335 accelerometer: For measuring acceleration that will be used in footsteps/
calorie burn calculation.
● MAX30102: High Sensitivity Pulse Oximeter and heart rate sensor to measure the
SpO2 and heart rate.
● Infineon dps310: Pressure Measuring Sensor for sitting.
● DHT11: A sensor to measure environment temperature & humidity.


Necessary Apparatuses:
_______________________
● Arduino uno: microcontroller board
● LCD display: for displaying message/data
● 74HC595: increase output pins of microcontroller
● Resistor: to prevent high voltage input
● Bread-board: connection setup and extension
● Connecting wire: connection setup
● Push button: to turn on off and customize options



Social Impact:
_______________

A healthier lifestyle: 
We often desire to incorporate positive habits into our lifestyle but are unable to do so since it is difficult to break free from our busy lives. The health tracker contains a number of features that help us stop bad habits and start living a better lifestyle.
Our system has the potential to play a key part in ensuring that we can maintain our health despite our hectic schedules.

Prevent Chronic Diseases:
 Certain disorders, such as back pain or shoulder pain, begin as minor ailments but progress to more serious conditions over time. We can stop these diseases
from getting worse by using our health-monitoring system. Early Detection of Diseases: Health disorders generally begin as mild irregularities. Our
health monitoring system can keep an eye out for these irregularities and send you early warnings, allowing you to intervene before things get out of hand.

Automatic measurement of Health readings:
 In case of any emergency the health readings need not to be measured manually rather the digital system will be providing the basic data.
