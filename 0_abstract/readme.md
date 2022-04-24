**ABSTRACT**

A Temperature Controlled DC Fan is a system which automatically turns on a DC Fan when the ambient temperature increases above a certain limit.

Generally, electronic devices produce more heat. So this heat should be reduced in order to protect the device. There are many ways to reduce this heat. One way is to switch on the fan spontaneously.

This describes two such circuits that automatically, switches the fan when it detects the temperature inside the device greater than its threshold value.

**PRINCIPLE**

The project works on the principle of Analog to Digital Conversion. The Analog data from the LM35 temperature sensor is given to the analog to digital converter ADC0804.

The analog output of the temperature sensor will vary at 10mV per degree Celsius.

ADC0804 is an 8-bit ADC. For a reference voltage of 5V, we’ll get a resolution of 5V/28 = 20mV. Which means, this is the minimum change in the analog value from the sensor which is recognisable by the ADC IC.

As per the changes in the temperature, the output of the ADC is generated. The digital output of the ADC is given to Microcontroller to calculate the temperature and control the fan accordingly.
