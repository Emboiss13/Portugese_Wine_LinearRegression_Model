# Health Data Analysis Project

## Introduction
This Jupyter Notebook project focuses on analyzing health-related data for the state of Florida. The project uses only the following libraries: matplotlib, numpy (imported by %pylab), pandas, scipy, and statsmodels.api. The primary tasks involve analyzing data on health indicators, specifically the percentage of smokers, teen birth rate, violent crime rate, and years of potential life lost rate.

## Project Structure

### **CELL1**
**Task:** Analyzing data regarding health in Florida.

**Steps:**
1. Read data from the text file '2017Health.txt'.
2. Isolate data from specific columns: 'Percentage Smokers', 'Teen Birth Rate', 'Violent Crime Rate'.
3. Calculate mean, minimum, and maximum for each health indicator.
4. Calculate margin of error and 95% confidence interval for each health indicator.
5. Display the results in a table.

### **CELL2**
**Task:** Analyze data on "Years of Potential Life Lost Rate" in specific counties in Florida.

**Steps:**
1. Filter data by regions: North, Central, South.
2. Calculate the mean and margin of error for the "Years of Potential Life Lost Rate" in each region.
3. Plot a bar graph to visualize the data for each region.

### **CELL3**
**Task:** Statistical Difference Analysis

**Methods:**
1. **Visual Test:**
   - Plot error bar graphs and histograms to visually compare the means and confidence intervals for different regions.

2. **Statistical Calculations:**
   - Perform normality tests and Mann-Whitney U tests to statistically compare the datasets.
   - Provide a concise conclusion for each comparison, including information on normality tests, t-tests, and Mann-Whitney U tests.

## Usage

1. Run the cells in sequence to perform the analysis step by step.
2. Visualizations, including error bar graphs and histograms, are saved as image files for reference.
3. The statistical conclusion for each comparison is provided based on the analysis performed in CELL3.

**Note:** Ensure the '2017Health.txt' file is present in the working directory for proper execution.

---

*Note: The conclusions and visualizations provided in this project are based on the specific health indicators mentioned in the dataset and may not cover a comprehensive analysis of overall health conditions.*
