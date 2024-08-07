# Bank Statement Analysis
I took on a project challenge which involved analyzing and visualizing my bank statement for 2024 so far to determine my spending habits, saving habits, financial health etc., and the following steps were taken:

### Step 1: Data Collection
- I downloaded an Excel file of my bank statement (January - July) from my online banking account.

### Step 2: Data Cleaning
- Imported the downloaded file into Excel.
- Removed unwanted rows.
- Filled in the blank cells for credit and debit with ₦0.00 where needed. 
- Standardized my date format and also my credit and debit columns as well. 
- Categorized my transactions into groups such as expenditure, data purchase, transportation etc., for better comprehension. 
- In Power BI, I made use of new measures and new columns to create my DAX functions of which I created a new table and also made calculated columns as well. 

### Step 3: Data Analysis
With the use of pivot tables, I was able to come up with insights on:
- Spending habits: I was able to check the sum of my debits for each category and identify months with highest spending based on those categories.
- Total credit and total debit
- Saving habits: which was done by subtracting total debit from total credit for each month. And I was able to identify months with negative saving. 
- Financial health: I determined what was eating up my finances based on the category with the highest debit.

### Step 4: Data Visualization
I created a dashboard making use of Power BI. Visual insights were gotten using KPIs and charts like Line chart (to show trends), Clustered Column chart (to show distribution), Pie chart (for comparison) and Tables. I also made use of filters for Months and Description (Categories) to filter information from the dashboard. 

### Key Insights
1. I had a total credit of ₦1.02 million, total debit of ₦1.41 million and savings of -₦386,895.
2. Spending habit: I was able to deduce that expenditure consumed majority of my money (₦514,950). And surprisingly, I had spent so much on data purchase (₦81,500).
3. Monthly spending: The clustered column chart shows the distribution of  total credit and total debit across the various months of which the month of May had the highest Total debit (₦486,076) and total credit (₦448,533).
4. Saving habit: I performed really poorly in the area of savings. I had more months with negative savings of which January was the worst (-₦290,974).
5. Investment habit: I also discovered that I didn't make room for any investment.
6. Financial health: With everything, it shows that my financial health is poor, and I need to do better in areas of my spending and savings. 

## Recommendations 
1. Create a budget: Have a monthly budget where expenses are categorized e.g., groceries, rent, transportation, data purchase etc. This helps to avoid unnecessary spending. 
2. Invest: Make room for investment. It is a good practise to spread investments across different sectors.
3. Set financial goals: These can be short or long term goals.
4. Emergency fund: Save for emergencies. This could be in form of automatic weekly or monthly transfers to the emergency fund.
5. Review financial status: Periodically review your financial situation, including budgets, investments, and financial goals to ensure you’re on track.
