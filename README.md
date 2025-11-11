# Does Tip Calc 
A C++ tip distribution calculator designed for dominos staff.  
Calculates fair tip splits based on hours worked, rounds cleanly to the dollar, and prevents rounding bias.

## Features
- Input validation for employees, hours, and total tips
- Fair rounding algorithm using remainders
- Tabular formatted output with aligned columns
- Replay option for multiple runs

## Example Output

----- Tip Distribution Results -----
Total Tips: $600 | Total Hours: 217.00 | Employees: 3
--------------------------------------
Name                   Hours        Tips
--------------------------------------
Mark                   85.00         235
Kevin                  60.00         166
Ryan                   72.00         199
--------------------------------------
All $600 successfully distributed!
If you would like to restart and calculate more tips, please enter Y. If not, enter any other character:
