# RTD-Thermistor_Thermocouple
Design of RTD, Thermistor, and Thermocouple sensors based on datasets of temperatures and equivalent resistance values.

1- RTD:

First, we find the coefficients of the equation by using the RTD.mat file, and cftool in MATLAB (using the least squares method).

<img src="images/IMG_4957.jpg" width="270" height="250">

<img src="images/IMG_4958.jpg" width="500" height="250">

It is shown that the value of alpha is equal to 0.0067, so the corresponding metal used in the sensor is Nickel, according to the table below:

<img src="images/IMG_4959.jpg" width="450" height="230">

The RTD circuit is as follows:

<img src="images/IMG_4960.jpg" width="400" height="300">

In the next step, a circuit is designed to convert the output of the sensor to a voltage in the range of 0 to 10 volts. The circuit is then tested in Proteous application as below:

<img src="images/IMG_4961.jpg" width="500" height="250">

2- Thermistor:

The coefficients of the equation by using the Thermistor.mat file, and cftool in MATLAB:

<img src="images/IMG_4963.jpg" width="500" height="500">

By writing the coresponding equations, we find the values of each component in the circuit, the values are found as below: 

R2 = 0.0155 KOhm

Vin = -20.2136 V

The circuit is designed to convert the output of the sensor to a voltage in the range of 0 to 10 volts. The circuit is then tested in Proteous application as below:

<img src="images/IMG_4965.jpg" width="400" height="400">

3- Thermocouple:

The coefficients of the equation by using the Thermistor.mat file, and cftool in MATLAB:

<img src="images/IMG_4966.jpg" width="500" height="500">

The equation above can be later used to design the corresponding circuit. The circuit is designed to convert the output of the sensor to an electric current in the range of 4 to 20 ampers. The circuit is later tested in Proteous application:

<img src="images/IMG_4968.jpg" width="600" height="350">
