# PySpark Date Range Calculations 

## Overview

This repository demonstrates how to perform date range calculations using PySpark within Databricks. The script calculates the date range for the previous year based on a given date range and extracts the date and year components.

## Setup in Databricks

### 1. Create a Databricks Notebook

1. **Log in to your Databricks workspace.**
2. **Create a new notebook**:
   - Click on `New` and then `Notebook`.
   - Name the notebook (e.g., `DateRangeCalculations`).
   - Choose `Python` as the language.

### 2. Copy and Paste the Code

Copy the code from the `date_range_calculations.py` file and paste it into the Databricks notebook. Here is the code snippet:

### 3. Run the Notebook

1. **Attach the notebook to a cluster**:
   - Click on the `Attach` button at the top of the notebook.
   - Select an existing cluster or create a new one.

2. **Run all cells**:
   - Click on `Run All` to execute the notebook cells and view the results.

## Code Explanation

- **Date Conversion**: Converts string date ranges to `date` format.
- **Last Year Date Range Calculation**: Computes the start and end dates for the same range in the previous year.
- **Extracting Components**: Extracts date and year components from the computed last year's dates.
  
   ![image](https://github.com/user-attachments/assets/f0ed87bc-7a75-4cbe-afe4-bf5f07a474ce)


## Notes

- Ensure that the date range values (`date_range_start` and `date_range_end`) are set according to your specific requirements.
- You can modify the code to read from or write to Databricks file storage if needed.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

This README provides clear instructions for setting up and running your code in a Databricks environment. Adjust any specific details as needed for your project!
