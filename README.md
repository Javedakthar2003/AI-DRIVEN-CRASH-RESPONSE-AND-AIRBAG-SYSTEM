# AI-DRIVEN-CRASH-RESPONSE-AND-AIRBAG-SYSTEM

Car Safety System With Airbag Notification


Every year the lives of approximately 1.3 million people are cut short as a result of a road traffic crash. Between 20 and 50 million more people suffer non-fatal injuries, with many incurring a disability as a result of their injury.
Road traffic injuries cause considerable economic losses to individuals, their families, and to nations as a whole. These losses arise from the cost of treatment as well as lost productivity for those killed or disabled by their injuries, and for family members who need to take time off work or school to care for the injured. Road traffic crashes cost most countries 3% of their gross domestic product.
Here are some facts about airbags
•	Airbags reduce fatalities of front-seat passengers older than 13 by 32%.
•	Side airbags can reduce an SUV driver’s risk of death by 52%.
•	From 1987 to 2017, front airbags have saved 50,457 lives in the United States.
•	India has tightened its rules on road safety making a 6 airbag compulsory rule for auto manufacturers from 2022.
The system aims to demonstrate a safety system for driver of the car. It has three features which will either alert or notify the concerned party about unfortunate accidents happened to the car and its passengers.
The first feature detects whether the driver of the car is feeling drowsy while driving or not. This is done using a camera which is controlled by the Raspberry Pi. If the driver is drowsy the system alerts using speakers that calls out a unique line and it takes a photo of the driver and sends it to the IoT page which can be useful in alerting other passengers in the car about the Drivers Drowsiness.
The second feature includes a vibration sensor which can detect any jerks that the car may receive after its impact or accident. The vibration sensing is paired with a GSM alert notification to the hospital and a police station whose number will be registered at the start of the system. An airbag is also attached in the system which will fill up after the accident is detected. The airbag is filled using an electric air pump. If the vibration sensor detects any jerks or vibrations it will trigger the electric air pump to fill the airbags minimizing harm to the passengers and sends an alert to the hospital and police stations numbers from the users sim card through GSM module. The electric air pump also has a cut off feature which leads us to our third feature.
This feature includes a SMS notification to the police station if the airbags are not opened on time (This feature can actually be illustrated in real-life better because the car can malfunction at any time in real-life, but for this project we have used an AC switch to cut off the supply to the electric air pump and illustrate the real-life example). This is detected using a limit switch which is placed in the system which is only triggered when the airbags are fully filled and if this does not happen within a certain time window an alert is issued as mentioned above.






Components
•	Raspberry Pi
•	Camera Module
•	Air Pump
•	Airbag
•	GSM Module
•	Vibration Sensor
•	AC Switch
•	Limit Switch
•	LCD Display
•	Regulatory Circuitry
•	PCB Board
•	Resistors
•	Capacitors
•	Transistors
•	Cables and Connectors

Block Diagram
 
![image](https://github.com/user-attachments/assets/a0e1809a-5386-4682-8364-b842ac3acd30)

