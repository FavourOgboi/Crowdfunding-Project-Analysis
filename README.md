# Crowdfunding Project Analysis
<img src="https://equito.co/app/uploads/2022/05/Equito-How-to-analyze-a-crowdfunding-project-600x326.jpg" alt="Crowdfunding Project Analysis" style="width: 100%; height: auto;">

---

## Overview

Crowdfunding platforms like Kickstarter and Indiegogo have grown significantly since the late 2000s. This project aims to analyze a dataset of 1,000 crowdfunding projects to uncover trends and insights that may contribute to the success or failure of campaigns. The analysis is performed using Microsoft Excel, employing various data manipulation and visualization techniques.

<img src="https://static.bc-edx.com/data/dl-1-2/m1/lms/img/FullTable.jpg" alt="Crowdfunding Project Analysis" style="width: 70%; height: auto;">

---

## Project Structure

The project is organized into several key parts:

1. **Data Preparation and Cleaning**
2. **Conditional Formatting**
3. **Pivot Tables and Charts**
4. **Crowdfunding Goal Analysis**
5. **Statistical Analysis**
6. **Insights and Conclusions**

---

## Data Preparation and Cleaning

- **Percent Funded:** A column calculated to show the percentage of the funding goal that was achieved.
- **Average Donation:** A column to determine the average donation per backer.
- **Parent Category and Sub-Category:** Columns created by splitting the original Category and Sub-Category column.
- **Date Conversion:** Converting Unix timestamps to Excel-readable date formats for launch and deadline dates.

---

## Conditional Formatting

- **Outcome Column:** Conditional formatting applied to visualize the status of each campaign (successful, failed, canceled, live).
- **Percent Funded Column:** Conditional formatting with a three-color scale to illustrate the funding success rate.
  
<img src="https://static.bc-edx.com/data/dl-1-2/m1/lms/img/CategoryStats.jpg" alt="Crowdfunding Project Analysis" style="width: 100%; height: auto;">

---

## Pivot Tables and Charts

<img src="https://static.bc-edx.com/data/dl-1-2/m1/lms/img/SubcategoryStats.jpg" alt="Crowdfunding Project Analysis" style="width: 100%; height: auto;">

### Category Stats
- A pivot table and a corresponding stacked-column pivot chart to analyze the number of campaigns by their outcomes per category, with a filter option by country.

### Subcategory Stats
- A pivot table and a stacked-column pivot chart to analyze the number of campaigns by their outcomes per sub-category, with filter options by country and parent category.

### Outcomes Based on Launch Date
- A pivot table and a line graph to visualize campaign outcomes based on their launch dates, with filters for parent category and year.

---

## Crowdfunding Goal Analysis

<img src="https://static.bc-edx.com/data/dl-1-2/m1/lms/img/GoalOutcomes.jpg" alt="Crowdfunding Project Analysis" style="width: 100%; height: auto;">


- **Goal Ranges:** Analysis of campaigns based on various goal ranges.
- **Success Rates:** Calculation of the percentage of projects that were successful, failed, or canceled within each goal range.
- **Visualization:** A line chart illustrating the relationship between goal amounts and their success, failure, or cancellation rates.

---

## Statistical Analysis

- **Campaign Backers:** Summary statistics for the number of backers in successful and unsuccessful campaigns, including mean, median, min, max, variance, and standard deviation.
- **Insights on Variability:** Understanding whether successful or unsuccessful campaigns show more variability and what that implies.

---

## Key Insights and Conclusions

1. **Three Conclusions:**
   - Successful campaigns often have moderate funding goals and a higher number of backers.
   - Campaigns with very high or very low goals tend to have lower success rates.
   - The timing of the campaign launch plays a significant role in determining its outcome.

2. **Dataset Limitations:**
   - Potential biases in the dataset.
   - Data accuracy and completeness.
   - Temporal limitations and potential seasonal effects.

3. **Suggestions for Further Analysis:**
   - Analyzing the impact of campaign duration on success rates.
   - Investigating the role of different promotional strategies.
   - Correlation between the number of updates/engagements and campaign success.

---

## Getting Started

To explore the analysis and replicate the results:

1. Download the project files from the repository.
2. Open the Excel workbook and follow the analysis steps outlined above.
3. Review the pivot tables, charts, and statistical summaries.

---

## Contributing

If you have any suggestions or improvements, feel free to fork the repository and submit a pull request. Contributions are welcome!

---

## Contact

For any questions or inquiries, please contact [Vincent Favour](https://www.linkedin.com/in/vincent-favour-297433205/).

---
