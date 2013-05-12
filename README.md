temperUSB
=========

Code to control a temperUSB thermometer.  Originally authored by Robert Kavaler.

This runs in 2 modes, repeat and single pass.  Run without parameters for single pass.  Pass any integer large than 0 to get repeat.

Repeat will track the min, max, and current temperature for the current run. (Min and max will reset each time the program runs).  Also the program now writes the date and temperature (in Farenheight) to a json file for the current, min, and max.

Single pass will create a JSON file with only the current temperature and date in it.

I will create a separate program to consume this data file.


Build Instructions
------------------
	make clean
	
	make all
	
Usage Instructions
------------------
On Unix systems, this program requires system priviledges in order to run.

	sudo ./temper