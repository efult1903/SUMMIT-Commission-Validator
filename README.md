# SUMMIT-Commission-Validator
This program aims to detect points of concern in our commission spreadsheets.
It will flag the following:
	- Commissions where we are being paid $1 less or $1 more than what we should be getting paid
	- Spreadsheets that do not list the Commission Rates
	
To get started, open the CommissionValidator 
(The one with the blue character and says "Application" on the right side)

[Uploading Your CSV File]
Then, select "Upload CSV file", you will be able to choose any .CSV file on your computer.
It should have an excel icon if it is a .csv file. I recommend placing the .csv file you want
either on your desktop or in the Commission Validator folder.
IMPORTANT: PLEASE MAKE SURE THE ROWS ARE JUST DATA.
THE PROGRAM WILL NOT WORK IF THE COLUMN NAMES ARE PLACED IN A ROW BESIDES THE HEADERS

[Column Selection]
Once you select it, you will see 3 dropdown menus. Select the appropriate column in your spreadsheet.
	- Base Premium: The total amount per month the person is paying
	- Commission Rate: The percentage of our commission from the Base Premium total
	- Commission Paid: The commission we are currently being paid.

[Analysis Results]
If no issues are present, the program will notify you and shut itself off.
If there are issues, you will see the Record number and the information related to the issue.
(nan means the spreadsheet cell was empty, which triggers the Missing Data flag)

[Refresh Analysis]
After this, you may make changes to the CSV file and 
click "refresh analysis" for an updated version

If you do not need to do that, then you may either close the program
or click "Calculate Missing Commission Rates"

[Calculate Missing Commission Rates]
Upon clicking this option, another window will pop up.
It displays the Base Premium and the Commission Paid.
Then, it will display what the Commission Rate should be if the data were not missing
If you would like to save this information, you may click "Save Estimates to 'estimate-rate.csv'"
Otherwise, you may X out of it or click "Close"

[End]
After you are done with the program, you may X out of the program.
If you saved the estimates, you will now be able to access that info in Excel
However, remember to not remove the "estimate-rate" CSV from the folder,
either copy it or access it from the folder.
