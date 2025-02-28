# README - Excel Case Studies and Lessons Learned

## Case Study 1: Sales Data Analysis

### Data Explanation:
The sales dataset contains transaction records, including the date, product type, sales region, sales representative, quantity sold, unit price, and total revenue. This data helps in analyzing revenue distribution across different regions, identifying top-performing sales representatives, and evaluating product sales trends to make informed business decisions.

Tasks:

1. Find total revenue for each region using a Pivot Table.

2. Calculate the total sales made by each Sales Rep using SUMIFS().

3. Create a bar chart to compare total revenue by region.

4. Highlight the top 5 highest sales transactions using Conditional Formatting.

  ![image alt](https://github.com/bbudha77/Excel-interview-practice-/blob/e2f7d29f613f30530b66afc9e8815511716ee471/Screenshot%202025-02-28%20221741.png)
  
### Lessons Learned:
- Pivot Tables are powerful for summarizing data quickly.
- `SUMIFS()` is useful for filtering and summing data based on conditions.
- Data visualization enhances insights and comparisons.
- Conditional Formatting makes it easier to spot key trends in large datasets.

---

## Case Study 2: Customer Churn Analysis

### Data Explanation:
The customer churn dataset records customer information, including their join date, last activity date, monthly plan value, and current status (active or churned). It helps businesses track customer retention, understand churn behavior, and identify potential improvements in customer engagement and pricing strategies.

Tasks:

1. Calculate the number of active and churned customers using COUNTIFS().

2. Find the average Monthly Plan value for churned customers using AVERAGEIFS().

3. Identify customers who haven't used the service in the last 6 months using IF() and TODAY().

4. Create a Pie Chart to show the proportion of Active vs. Churned customers


![image alt](https://github.com/bbudha77/Excel-interview-practice-/blob/65863af92e956a55b895c397245ef0d39be394be/Screenshot%202025-02-28%20222012.png)

### Lessons Learned:
- `COUNTIFS()` and `AVERAGEIFS()` are essential for filtering data.
- `IF()` with `TODAY()` helps track recency-based conditions.
- Pie charts are effective for showing proportions in datasets.

---

## Case Study 3: Employee Performance Dashboard

### Data Explanation:
The employee performance dataset includes details on department, tasks completed, hours worked, and efficiency percentage. This data helps monitor productivity, highlight high-performing employees, and assess workload distribution across different departments to optimize workforce efficiency.  

Tasks:

1. Calculate Efficiency (%) using the formula:

= (Tasks Completed / Hours Worked) * 100

2. Find the top-performing employee using LARGE() and INDEX().

3. Use Conditional Formatting to highlight employees with efficiency above 30%.

4. Create a dynamic dashboard using a Pivot Table and Slicers.

![image alt](https://github.com/bbudha77/Excel-interview-practice-/blob/eacaa8753aeed9563e1901981c03d5ce93d6dd88/Screenshot%202025-02-28%20224930.png)

### Lessons Learned:
- Efficiency formulas provide clear performance metrics.
- `LARGE()` and `INDEX()` help in ranking and retrieving top records.
- Conditional Formatting enhances readability of key insights.
- Pivot Tables with Slicers make dashboards dynamic and user-friendly.

---

## Excel Formula Challenge


Task: 

Write a formula to find the third highest revenue in a sales dataset.

![image alt](https://github.com/bbudha77/Excel-interview-practice-/blob/cc9c994418759ef795a003c8314ef9aba7d73645/Screenshot%202025-02-28%20223633.png)
### Lessons Learned:
- The `LARGE()` function is useful for ranking data without sorting.
- Understanding indexed ranking helps in dynamic analysis.

---

## Data Cleaning Challenge


Task: Clean the data using Excel functions like:

=PROPER(A2) ' Fixes capitalization

=TRIM(B2) ' Removes extra spaces

=SUBSTITUTE(C2, "-", "") ' Removes dashes

### Lessons Learned:
- `PROPER()` ensures consistency in text formatting.
- `TRIM()` helps clean unnecessary spaces, making data more uniform.
- `SUBSTITUTE()` is valuable for standardizing inconsistent data formats.

  ![image alt](https://github.com/bbudha77/Excel-interview-practice-/blob/177564369034045b5d9c3b2549cbed0272de7115/Screenshot%202025-02-28%20222152.png)

---

## Final Thoughts
- Structuring data properly makes analysis easier.
- Using the right Excel functions can save significant time.
- Data visualization and formatting improve decision-making.
- Dynamic dashboards provide better interactivity and insights.

Happy Analyzing!





