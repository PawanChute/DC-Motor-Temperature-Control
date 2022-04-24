**Components**

Atmega8

L293D

Lm35

DC motor

**Component Description**

**LM35**

The LM35 is an integrated circuit sensor that can be used to measure temperature. The output voltage of this sensor is proportional to the temperature in degree Centigrade. The output voltage of the LM35 will vary at a rate of 10mV per degree Celsius.

Usually, the range of the LM35 temperature sensor is from -55 deg C to +150 deg C. To measure this full range of temperatures i.e. from negative range to positive range, we need to connect an external resistor between the data pin and a negative supply of Vcc.

Any way, we are not going to consider the negative temperature range in this project. So, under normal operating conditions, we can measure the temperature in the range from +2 deg C to +150 deg C.

**ADC**

All the parameters of nature are of analog i.e. most of the data in the real world is characterised by analog signals. For instance, if the temperature of the room is measured.

The room temperature varies with time continuously. This measured signal, which continuously changes with time say from 1sec , 1.1sec , 1.2 sec and so on is called Analog signal.

In order to manipulate the real world data using a microprocessor or a microcontroller, we need to convert the analog signals to the digital signals, so that the processor or controller will be able to read, understand and manipulate the data.

Atmega8 has internal Analog to digital converter.
