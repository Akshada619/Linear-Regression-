# Linear-Regression-

## Energy Consumption Dataset

## Overview :-

This dataset contains information related to energy consumption in buildings based on various factors such as room area, number of appliances, outside temperature, insulation thickness, building type, HVAC system, and average temperature.

## Dataset Information :-

The dataset is useful for regression tasks, particularly in predicting energy consumption based on environmental and structural parameters. The target variable is EnergyConsumption.

## Column Descriptions :-
The dataset includes the following columns:

1) RoomArea (float/integer, units: assumed square feet or meters)
   The area of the room or building.
   Example: 302, 470
   
2) NumberofAppliances (integer)
   The total number of electrical appliances in the building.
   Example: 5, 17
   
3) Outside Temperature (float, units: assumed Celsius)
   The external temperature at the time of measurement.
   Example: -9.638784, 13.536505
   
4) InsulationThickness (float, units: assumed inches or centimeters)
   The thickness of the insulation in the building walls or structure.
   Example: 7.227564, 1.086168
   
5) BuildingType (categorical: Residential, Commercial)
   The type of building.
   Example: Residential, Commercial
   
6) HVACSystem (categorical: Window AC, Split AC, Central AC)
   The type of HVAC system installed in the building.
   Example: Window AC, Central AC
   
7) AverageTemperature (float, units: assumed Celsius)
   The average internal temperature of the building.
   Example: -8.444161, 15.267517
   
8) EnergyConsumption (float, units: assumed kWh or similar energy unit)
   The total energy consumed by the building over a given period (time period 
   unspecified).
   Example: 1828.820920, 2307.834235

## Usage :-
This dataset can be used for various applications, such as:

a)Predicting energy consumption based on environmental and building parameters.
b)Optimizing HVAC system efficiency based on external and internal factors.
c)Conducting research on energy efficiency in different building types.


## Example Use Case :-

A machine learning model can be trained using this dataset to predict EnergyConsumption based on the other features. The R² score (coefficient of determination) can be used to evaluate model performance in regression tasks.
