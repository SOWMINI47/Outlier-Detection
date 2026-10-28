# Outlier Detection Using Box Plot

## Project Overview
This project demonstrates basic outlier detection using a box plot and the Interquartile Range (IQR) method. A sample employee salary dataset is analyzed using Python, Pandas, and Matplotlib.

## Objective
Understand how box plots visualize numerical data and help identify potential outliers.

## Tools and Technologies
- Python
- Pandas
- Matplotlib
- Google Colab / Jupyter Notebook

## Dataset
The notebook creates a sample employee salary dataset with:
- `Employee`: employee name
- `Salary`: numerical salary value

## Methodology
1. Create and display the dataset.
2. Visualize salary values using `plt.boxplot()`.
3. Calculate the first quartile (Q1), third quartile (Q3), and interquartile range (IQR).
4. Calculate the boundaries:
   - Lower bound = Q1 - 1.5 × IQR
   - Upper bound = Q3 + 1.5 × IQR
5. Display values outside the boundaries.
6. Explain the findings without automatically removing any values.

## Expected Finding
The sample data includes a salary of 200000, which should be flagged as a potential outlier. It should be investigated before deciding whether it is an error or a valid value.

## How to Run
1. Download `Outlier_Detection.ipynb`.
2. Open [Google Colab](https://colab.research.google.com/).
3. Select **File → Upload notebook** and upload the notebook.
4. Select **Runtime → Run all**.
5. Review the box plot, IQR boundaries, and output.

## Conclusion
Box plots and the IQR method provide a simple way to identify unusual numerical values. Potential outliers should be investigated in context before changing the data.
