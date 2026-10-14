# Medical-Device-Quality-Inspection-Automation
A beginner RPA project using Power Automate Desktop to flag out-of-range inspection measurements and missing inspector information
# Medical Device Quality Inspection Automation System

## Project Overview
This beginner-level project demonstrates the use of Robotic Process Automation (RPA) in a medical-device quality inspection workflow using Microsoft Power Automate Desktop.

The workflow processes fictional inspection records, checks measurements against predefined limits, and identifies missing inspector information for review.

## Objectives
- Automate reading inspection data from a CSV file.
- Compare measured values against predefined upper and lower limits.
- Identify records with missing inspector information.
- Generate a text report highlighting records requiring review.

## Tools Used
- Microsoft Power Automate Desktop
- CSV data
- Text-file reporting

## Workflow
1. Read inspection records from a CSV file.
2. Process each inspection record.
3. Check measurements against predefined limits.
4. Identify missing inspector information.
5. Generate a report of records flagged for review.

## Project Files
- `Inspection_Data.csv` — fictional inspection dataset.
- `Inspection_Report.txt` — sample output from the prototype.
- Workflow screenshots — visual documentation of the automation.

## Learning Outcomes
This project helped me practise conditional logic, file handling, data validation, and exception reporting using RPA.

## Limitations
This is a learning prototype using fictional data. The workflow requires verification of its comparison logic and output before its results can be relied upon. It is not intended for actual medical-device quality decisions or device-release decisions.

## Future Improvements
- Correctly validate numeric comparisons and boundary conditions.
- Improve error handling and reporting.
- Add summary counts for records flagged for review.
- Explore integration with Excel or Power BI for reporting.

**Disclaimer:** This project is for educational and portfolio demonstration purposes only.
