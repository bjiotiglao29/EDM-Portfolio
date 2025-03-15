![3](https://github.com/user-attachments/assets/d8be0019-3794-4f4f-a9be-b5bdc1f1193c)

# Midterm Lab Task 2
-  In this task, I cleaned and transformed a dataset using Power Query in Excel. I removed unnecessary characters, created new salary columns, categorized job roles, and standardized location data. I handled negative values, cleaned company info, and grouped the data by role, size, and state. Finally, I mapped state abbreviations and summarized the salary data.

## Step by step process
1. **Download the Dataset**: Download the file named "Uncleaned_DS_jobs.csv."
2. **Load Data in Excel**: Open Excel -> Go to Data -> New Query -> Open File -> Choose "Text/CSV."
3. **Edit Data**: Use Power Query Editor to make changes to the dataset.

### Data Cleaning Tasks:
4. **Salary Estimate Cleaning**:
   - Remove all text after the "(" in the "Salary Estimate" column.
   - Use the "Extract" function under the "Transform" menu to get text before the "(".

5. **Create Min and Max Salary Columns**:
   - Duplicate the "Salary Estimate" column.
   - Create two new columns: "Min Sal" and "Max Sal" by selecting the "Salary Estimate" column and following the steps to add these columns based on examples.
   
6. **Create "Role Type" Column**:
   - Add a new column to group job titles (e.g., Data Scientist, Data Analyst).
   - Use a custom formula to categorize jobs, like “Data Scientist,” “Data Analyst,” etc.

7. **Split Location Column**:
   - Split the "Location" column using commas as delimiters.
   - If there are no commas, use a custom column to standardize locations (e.g., New Jersey to "NJ").
   - Split and rename the columns for location corrections and abbreviations.

8. **Handle Negative Values**:
   - Filter out negative values and clean the data for columns like "Competitors" and "Revenues."

9. **Remove Unnecessary Columns**:
   - Clean up the company names and descriptions, and remove unwanted columns.

10. **Copy Applied Steps**:
   - Go to Home -> Advanced Editor to copy the steps for your data cleaning.

### Reshape and Group Data:
1. **Duplicate Raw Data**:
   - Duplicate the raw data and rename it as "Sal By Role Type dup."
   - Choose columns for "Role Type," "Min Sal," and "Max Sal," and adjust them to currency format.
   - Multiply the salary values by 1000, then group by "Role Type" and calculate the averages.

2. **Create "Sal By Role Size"**:
   - Duplicate the raw data and rename it as "Sal By Role Size ref."
   - Choose "Size," "Min Sal," and "Max Sal," and repeat the same steps as above to get averages by "Size."

3. **Map State Abbreviations**:
   - Add state mapping data to the queries.
   - Merge the state abbreviations to match full state names and clean up any blank or null values.

4. **Group by State**:
   - Create a reference for "Sal By State ref."
   - Choose "State Full Name," "Min Sal," and "Max Sal," and group by "State Full Name" to get average salaries by state.

5. **View Dependencies**:
   - Go to View -> Dependencies to check the relationship between the queries and ensure they are correct.

### Screenshots/Documentation of the cleaning process

![3](https://github.com/user-attachments/assets/9805f323-5864-4f27-a743-22330702ddb4)
![4](https://github.com/user-attachments/assets/e28e40d2-26cf-4a13-acec-7206d237d990)
![1](https://github.com/user-attachments/assets/47d14a0d-dac7-45e8-9593-3907efe7ea1f)
![2](https://github.com/user-attachments/assets/4fd1320a-0432-4e8f-b4c2-4b722cd64dce)
