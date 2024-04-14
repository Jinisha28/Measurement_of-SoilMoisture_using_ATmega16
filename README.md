# Measurement_of-SoilMoisture_using_ATmega16
First Interface Atmega16 with LCD and Soil Moisture Sensor. 
Ensure the given voltage should not be more than 5V. You can use voltage regulator to control the voltage incase you are giving voltage from 9V battery. The soil moisture sensor module, which gives output analog as well
as digital. Here, we will take the analog output from this module.
The output of the soil moisture sensor changes in the range of ADC value is 0 –
1023, and to show in percentage from the given formula,
Analog output = (ADC Value / 1023)
Moisture in percentage = 100 – (Analog output * 100)
For zero moisture, we get a 10-bit ADC value maximum i.e. 1023 which in turn
gives 0% moisture.
The code is written in C language in Atmel Studio 7.0 and the simulation is done in Proteus 8 Professional.
The soil moisture sensor library was also installed in proteus.
