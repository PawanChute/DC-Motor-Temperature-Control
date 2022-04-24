** How Temperature Controlled DC Fan Circuit using Microcontroller Works? **

Initially switch the power supply.
Microcontroller starts reading the temperature of the surroundings.
The analog value of temperature is given by the temperature sensor.
This analog value is applied to the analog to digital converter pin of the micro controller.
This analog value is converted to the digital value by the microcontroller using successive approximation method internally.
When the temperature is greater than the threshold value, microcontroller sends a command to the controller to switch the motor.
Thus fan starts rotating.
