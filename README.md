# excel-power-query-hr-analytics-
Excel Power Query project analyzing employee training completion, salary, and tenure
# HR Training Analytics with Excel Power Query

A Business Analytics coursework project at ADA University. I used Excel
Power Query to combine employee records with training data and report
training completion, salary, age, and tenure across employee groups.

## Power Query Workflow

1. Imported the Employee and Training tables.
2. Derived age from date of birth and tenure from hire date.
3. Merged the tables on `EmployeeID` and expanded the training name and status.
4. Created a `Status2` flag with `1` for completed training and `0` otherwise.
5. Loaded the transformed data into Excel and summarized it with PivotTables.

## Reports

- **By gender:** Employee count, average salary, minimum and maximum age,
  and training completion rate.
- **By department:** Average salary, training completion rate, and average tenure.

The workbook reports an overall training completion rate of **56.7%**
across **30 employee records**.

[Download the Excel workbook](hr-training-analysis.xlsx)
