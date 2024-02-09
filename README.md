# Health-monitoring-System

The objective of developing a monitoring system is to reduce healthcare costs by minimizing physician office visits, hospitalizations, and diagnostic testing procedures. This technology facilitates the server to update patient data on a website. The IoT-based real-time health monitoring system systematically monitors the condition of patients' health and saves lives by providing timely intervention.

Understanding IoT:

In its essence, the Internet of Things (IoT) describes the digitally connected universe of everyday physical devices. These devices are equipped with internet connectivity, sensors, and other hardware enabling communication and control via the web. IoT enhances formerly "dumb" devices by empowering them to send data over the internet, enabling communication with people and other IoT-enabled devices.

Problem Statement:

The COVID-19 pandemic has caused a global health crisis, resulting in numerous deaths daily. Minimizing the fatality rate requires timely administration of proper treatment. Despite efforts such as regular monitoring of pulse rate and temperature, the oxygen level of COVID-19 patients decreases over time, posing a severe risk if emergency steps are not taken promptly.

Apparatus:

NodeMCU
Temperature sensor - LM35
Heartbeat Sensor - MAX30102
Connecting Wires
Arduino IDE tool
IoT platform - ThingSpeak
LM35:

LM35 is a three-terminal linear temperature sensor that produces an output voltage proportional to the surrounding temperature. It operates within a temperature range of -55°C to 150°C, making it suitable for various applications. With an output voltage increment of 10mV per degree Celsius, LM35 provides precise temperature readings without requiring external calibration circuitry.

MAX30102:

Power Supply: 3.3V to 5.5V
Current Drawn: 600uA (during measurements), 0.7uA (during standby mode)
LED Wavelength: 660nm (Red LED), 880nm (IR LED)
Temperature Range: -40°C to +85°C
The MAX30102 sensor detects changes in the amount of IR light absorbed by oxygenated hemoglobin in arterial blood, providing heart rate (HR) pulse readings. By continuously illuminating the finger and taking photodetector readings, the sensor captures the changing waveform created by the pulsatile blood flow.

Observations:

The designed prototype underwent testing on various subjects to assess the performance of the health monitoring system. Heart rate and body temperature were measured as key parameters for performance analysis. The system's efficacy was evaluated by comparing the measured data with readings from commercial sensors. Minimal relative error was observed between the measured and actual values. Additionally, data analysis was conducted to predict future values and associated diseases. Graphical representations were obtained from ThingSpeak, triggering email alerts when values exceeded specified limits. This real-time monitoring ensures timely interventions, potentially saving lives.
