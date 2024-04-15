# evolve
### Technical Assessment Documentation

#### Overview

This technical assessment involves performing various data processing tasks using Python and Pandas library. The tasks include identifying duplicated invoices, extracting blocked vendors, calculating the total count of vendors with a specific name, and ranking vendors based on invoice amounts.

#### Problems and Solutions

1. **Identifying Duplicated Invoices:**
   - **Problem:** The task involved identifying duplicated invoices in a dataset.
   - **Solution:** The `value_counts()` method was used to count the number of appearances for each invoice number. The resulting DataFrame was then formatted and displayed using the `tabulate` library.

2. **Extracting Blocked Vendors:**
   - **Problem:** The task required extracting vendors with a specific status from a dataset.
   - **Solution:** The dataset was loaded from a CSV file, and relevant columns were extracted. Vendors with the specified status were filtered, and the resulting DataFrame was displayed using the `tabulate` library.

3. **Calculating Total Count of Vendors:**
   - **Problem:** The task involved counting the total number of vendors with a specific name.
   - **Solution:** The count of vendors with the specified name was calculated using the `value_counts()` method. The result was then formatted and displayed using the `tabulate` library.

4. **Ranking Vendors Based on Invoice Amounts:**
   - **Problem:** The task required ranking vendors based on the total amount of their invoices.
   - **Solution:** The dataset was processed to calculate the total invoice amount for each vendor. Vendors were then ranked based on their total invoice amounts and displayed in a tabular format using the `tabulate` library.

### Usage

1. Make sure to have Python installed on your system.
2. Install the necessary libraries (`pandas`, `tabulate`).
3. Download the provided dataset files (`Transactions.csv`, `VendorData.xlsx`) to your local machine.
4. Run the provided Python scripts in your preferred Python environment (e.g., Jupyter Notebook) to perform the specified tasks.
5. Customize the scripts or adjust the file paths as needed for your specific use case.

### Note

- Ensure that the dataset files are correctly located and named as per the script's requirements.
- If any errors occur during script execution, check the file paths and ensure that the dataset files are accessible.
