# unit-converter
Free spreadsheet-based unit converter

# Getting started
[Download](https://github.com/sashahafner/unit-converter/raw/main/unit-converter.xlsx) the unit-converter.xlsx file and open it in Excel, LibreOffice Calc, or similar spreadsheet programs.
Enter a input value, enter or select input and output units and exponents, and an output value is automatically calculated.
Check detailed error messages in red if no value is returned.
One common problem is a blank input unit cell. 
Be sure to use "." instead.
The examples below should be helpful for getting started.
To reset the tool, simply close the file without saving changes.

# Contact
For users with a GitHub account, use [Discussions](https://github.com/sashahafner/unit-converter/discussions) to send feedback or get help.
For bugs, [Issues](https://github.com/sashahafner/unit-converter/issues) is a more appropriate place.

Users without a GitHub account can find my contact information [here](https://au.dk/sasha.hafner@bce) or [here](https://sites.google.com/hafnerconsulting.com/hafnerconsulting).

# Examples
## 1. Water supply volume
How many cubic meters is 400,000 acre-feet of water?
![image](https://user-images.githubusercontent.com/35272876/211882171-bd631d8d-825f-43dd-b1c0-50c27af54252.png)

## 2. Convert flux units
What is the conversion factor needed to scale up this mass flux unit?
![image](https://user-images.githubusercontent.com/35272876/211879637-4031c89b-964e-466b-a867-adeb6cbd8e71.png)

## 3. Speed calcuation with a constant
How long does it take light to travel the 91.4 million miles from the Sun to Earth? 
![image](https://user-images.githubusercontent.com/35272876/211881719-a1e748e6-af6a-4099-816a-f31d90d681d8.png)
See the "C" sheet to find a description of the available constants.

## 4. Simple pressure conversion
![image](https://user-images.githubusercontent.com/35272876/212169989-fbe766de-3188-4483-9e21-fadad2382a13.png)

## 5. Set units for ideal gas constant
![image](https://user-images.githubusercontent.com/35272876/212171575-026cf3d7-2cc7-438a-b2ab-b5420b891e1d.png)

## 6. Convert auto fuel efficiency
Miles per gallong to L per 100 km.
This requires a bit of thinking to set up.
![image](https://user-images.githubusercontent.com/35272876/212348035-72e01bc5-903e-4529-a865-a2573f61ab08.png)

## 7. Kinetic energy problem
How much kinetic energy in kJ is in a 4000 lb car traveling at 60 mph? And how does that compare to a 200 lb bicycle (+ rider) traveling 20 mph?
For this we need to know that kinetic energy is given by 1/2 * m * v^2.
![image](https://user-images.githubusercontent.com/35272876/212388001-16e6c379-1dd1-4cec-bc22-dc1a6ab5238d.png)

![image](https://user-images.githubusercontent.com/35272876/212388084-048957aa-e858-45c9-9f75-543b91bd26fc.png)



# More details
Use the "Regular" sheet unless you want to carry out a calculation that includes constants (see example 3 above).

The S, D, F, and C sheets contain SI prefixes, dimensions, conversion factors, and constants.
Users can find descriptions (e.g., to check abbreviations) and sources in these sheets, or add additional factors or constants.

Calculations are carried out in some hidden sheets.
If interested, just use the right-click menu to "un-hide" or show the hidden sheets.
