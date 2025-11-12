![C++](https://img.shields.io/badge/language-C%2B%2B-blue.svg)
![Platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux-lightgrey.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Status](https://img.shields.io/badge/status-Stable-success.svg)



# Does Tip Calc 
A **C++ tip distribution calculator** designed for Dominos staff.  
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


## 📦 How to Run
1. Clone the repo
   ```bash
   git clone https://github.com/sv3dka/does-tip-calc.git
   cd does-tip-calc
3. Compile it
   ```bash
   g++ tipcalc.cpp -o tipcalc.exe

5. Run it
   ```bash
   ./tipcalc.exe

## License
This project is licensed under the MIT License — free to use, modify, and share.
