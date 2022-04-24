**Circuit Design**

The main components of the project are 8051 Microcontroller, 16×2 LCD Display, LM35 Temperature Sensor, ADC0804, Relay and Fan.

The basic connections with respect to microcontroller include clock, reset and EA. Clock consists of an 11.0592 MHz crystal and two 33pF capacitors. The reset circuit consists of a 10µF capacitor, 10KΩ resistor and a push button. The EA pin is pulled high with a 10KΩ resistor.

Now we’ll see the connections with respect to other components.

For the LCD display, a 10KΩ pot is connected to contrast adjust pin. The three control pins of the LCD are connected to the pins P3.6, GND and P3.7.

The 8 data pins of the LCD are connected to PORT1 of the microcontroller.

The basic connections with respect to ADC are explained in its configuration. The 8 digital outputs of the ADC must be connected to PORT 2 of the microcontroller.

The next component we are going to connect is LM35. Connect the data pin of the LM35 to the analog input pin i.e. Pin 6 of ADC.

Finally, we need to connect the Relay circuit consisting of resistor, transistor and relay to the PORT0 of the microcontroller with PORT 0 pulled-up externally.

Connect the input of relay i.e. base of the transistor to P0.0 pin of the microcontroller.

**Working**

The aim of this project is to design a temperature controlled fan using 8051 microcontroller, in which the fan is automatically turned ON or OFF according to the temperature. The working of the project is explained here.

In this circuit, the LM35 temperature sensor will give continuous analog output corresponding to the temperature sensed by it. This analog signal is given to the ADC, which converts the analog values to digital values.

The digital output of the ADC is equivalent to sensed analog voltage.

In order to get the temperature from the sensed analog voltage, we need to perform some calculations in the programming for the microcontroller.

Once the calculations are done by the microcontroller according to the logic, the temperature is displayed on the LCD. Like this, the microcontroller will continuously monitor the temperature.

If the temperature exceeds more than 50 deg Celsius (as per the code), the microcontroller will turn on the relay to start the fan. If the temperature drops below 40 deg Celsius (as per the code).



![Circuit-Diagram-of-Temperature-Controlled-DC-Motor](https://user-images.githubusercontent.com/101561885/164998585-4c7bd066-f533-4cd8-b062-c38a17f1581c.jpg)












