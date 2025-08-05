# TEMPERATURE-MONITORING-SYSTEM

COMPANY: CODTECH IT SOLUTIONS

NAME: SANJAY S V

INTERN ID: CT04DH842

DOMAIN: EMBEDDED SYSTEMS

DURATION: 4 WEEKS

MENTOR: NEELA SANTHOSH

TASK DESCRIPTION:

This task entails creating a simple embedded system that uses an Arduino UNO to display the temperature on a 16x2 I2C LCD and an LM35 sensor to measure the ambient temperature. Through the analog input pin of the Arduino, the LM35's analog output is read, and a formula is used to convert it to temperature (°C).  The I2C LCD screen shows the temperature in real time. Understanding analog signal processing, sensor interface, and I2C communication is aided by this task.

COMPONENTS USED:
   
    Arduino UNO

    LM35 Temperature Sensor

    16x2 I2C LCD Display

    Breadboard and Jumper Wires

WORKING PRINCIPLE:

10mV per degree Celsius is the output of the LM35.
 Arduino uses the following formula to read the analog voltage and translate it into a temperature value:
 (analogRead * 5.0 / 1023.0) * 100 = temperature (°C)
 The I2C LCD shows the computed temperature.
I2C LCD simplifies wiring by using just two pins:
SDA: A4
SCL: A5

OUTPUT:

![outputimage](https://github.com/user-attachments/assets/1dbc66d7-9678-4630-a394-8b1107c8cc6c)

