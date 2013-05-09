temperUSB
=========

Code to control a temperUSB thermometer.  Originally authored by Robert Kavaler.

I tweaked it to track the min, max, and current temperature for the current run. (Min and max will reset each time the program runs).  Also the program now writes the date and temperature (in Farenheight) to a json file for the current, min, and max.

I will create a separate program to consume this data file.


Build Instructions
------------------
	make clean
	
	make all
	
Usage Instructions
------------------
On Unix systems, this program requires system priviledges in order to run.

	sudo ./temper