# Arduino-Based-Pulse-Oximeter-Health-Monitoring
A easy DIY project for school and college, Which can measure BPM and oxygen level very accurately.
Get full info from here: https://www.instructables.com/Arduino-Based-Pulse-Oximeter-Health-Monitoring/

For PCB:
This is tested schematics, but the LCD only work on I2C port. Pins are just for understanding purpose. If you want to use same design as mine then Download the Gerber files from here. JLCPCB offering a very good service (just $2 for 5 Pcs).
Pulse oximeter:
A non-invasive medical device that utilizes spectrophotometry to measure the oxygen saturation of circulating arterial blood in an individual by determining the percentage of oxygenated haemoglobin pulsating through a network of blood capillaries by way of a sensor attached typically to a finger. This sensor used to measure BPM( Heart beat per minute) and Spo2(Oxygen level in blood).
A normal level of oxygen is usually 95% or higher. Some people with chronic lung disease or sleep apnoea can have normal levels around 90%. The “SpO2” reading on a pulse oximeter shows the percentage of oxygen in someone's blood. If your home SpO2 reading is lower than 95%, call your health care provider.
Difference Between BP and BPM:
The heart rate records the number of times that your heart beats per minute (BPM) , while your blood pressure quantifies how strong your blood moves through the blood vessels (BP).
Pulse Oximeter sensor:
MAX30100 is an integrated pulse oximeter and heart-rate monitor sensor solution. It’s an optical sensor that derives its readings from emitting two wavelengths of light from two LEDs – a red and an infrared one – then measuring the absorbance of pulsing blood through a photodetector. This particular LED colour combination is optimized for reading the data through the tip of one’s finger. It is fully configurable through software registers and the digital output data is stored in a 16-deep FIFO within the device. It has an I2C digital interface to communicate with a host microcontroller.
Features:
•	Measures absorbance of pulsing blood
•	I2C interface plus INT pin
•	Tiny 5.6mm x 2.8mm x 1.2mm 14-Pin Optically Enhanced System-in-Package
•	Ultra-Low-Power Operation Increases Battery Life for Wearable Devices
•	Programmable Sample Rate and LED Current for Power Savings
•	Ultra-Low Shutdown Current (0.7µA, typ)
•	Advanced Functionality Improves Measurement Performance
•	High SNR Provides Robust Motion Artifact Resilience
•	Integrated Ambient Light Cancellation
•	High Sample Rate Capability
•	Fast Data Output Capability
Components required:
1)	Arduino UNO 
2)	16X2 LCD (With I2C adapter)
3)	MAX30100 sensor
4)	Wires and breadboard
5)	Custom PCB
