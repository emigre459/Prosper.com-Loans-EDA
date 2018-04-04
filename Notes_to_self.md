# Data Sources and Relevant Uses

I have a bunch of data files that need to be joined on one another (in R?) and then loaded up for 
analysis. Here's what I have and how I intend to use it:

1. ElectricityEndUse_1949-2017.csv: this is effectively just energy demand by state over time.
	* Can use this to track energy efficiency over time, as that's in some ways the most "clean."
	* This will also allow me to weight different states' dirtiness by normalizing generation capacity
		to actual energy use.

2. CO2emissions_electricity_by_state_1980-2015.xlsx
	* Provides CO2 emissions from electricity alone by state
	* Different from CO2emissions_ALLSOURCES_1990-2015.xlsx in that ALLSOURCES covers more than
		electricity.
	* Provides the data about CO2 per kW and/or kWh of use

3. 