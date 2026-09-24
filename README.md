# -seasonal-crop-analysis
Seasonal agriculture performance analysis of 4,000 farm records across Kharif, Rabi and Zaid seasons, comparing yield, profit, water usage and environmental factors using Python, SQL and Jupyter Notebook.

Seasonal Agriculture Performance Analysis
A descriptive data analysis of 4,000 farm records across the Kharif, Rabi and Zaid seasons, comparing yield, profit, water usage and environmental conditions to support seasonal agricultural planning.
Overview
This project analyzes cleaned_agriculture_dataset.csv to understand how agricultural performance changes from one season to another. It answers 12 key questions covering seasonal patterns, resource usage, environmental relationships, economic outcomes and planning insights. The results are presented in a 15-slide PowerPoint deck.
Objective
To find out how yield, profit, water usage and environmental conditions vary across seasons, and to turn those observations into practical insights for seasonal planning.
Dataset
Item Details
File cleaned_agriculture_dataset.csv
Rows 4,000 (4,000 unique Farm_IDs)
Columns 28
Seasons Kharif, Rabi, Zaid
Crops 8
States 8
Missing values 0
Duplicate rows 0
Profit is consistent with Revenue − Total Cost for all 4,000 records.
Tools and Technologies
Jupyter Notebook for the analysis environment
Python and its libraries for data cleaning, validation, calculations and visualization
SQL for querying and aggregating the data
PowerPoint for the final presentation
Key Questions Answered
How does agricultural performance vary across seasons?
What major seasonal patterns can be observed?
Which characteristics change between seasons?
What differences exist between agricultural activities in different seasons?
Are there noticeable variations in resource usage across seasons?
Are there relationships between seasonal environmental conditions and agricultural performance?
How do economic outcomes vary across seasons?
Are some seasonal patterns consistent across different regions or categories?
Are there unusual or unexpected seasonal patterns?
What insights can be derived from the observed seasonal differences?
What conclusions can reasonably be drawn from the available data?
How could the findings support better seasonal agricultural planning?
Key Findings
Season Average Yield (t/ha) Average Profit (₹)
Kharif 5.629 178,914.65
Rabi 5.093 87,689.47
Zaid 4.633 −24,804.82
Kharif is the strongest season. It has the highest average yield and profit, and all 8 crops reach their highest average yield in Kharif.
Zaid is the weakest season. Its average profit is negative, and 64.48% of its records are loss-making.
Losses are widespread. Overall, 1,966 of 4,000 records (49.15%) are loss-making.
Environmental factors are weak predictors on their own. Linear correlations between environmental variables and yield are generally weak.
Resource use varies by season. Water usage and water-use efficiency differ across seasons.
Data Handling Decisions
All calculations use the full 4,000-row dataset, with no sampling.
No outliers were removed. Sugarcane's very high yield was kept as a genuine crop characteristic.
State and District values were left as provided, even where they do not match real geography, so crop-level comparisons are more reliable than State-District comparisons.
Limitations
The analysis is descriptive. The results show patterns in this dataset and should not be treated as proof of causation.
State and District inconsistencies limit region-level conclusions.
Causal claims would require additional controlled or longitudinal data.
Planning Insights
Use Kharif's production and profitability profile as a benchmark for seasonal planning.
Treat Zaid as a higher-risk season financially.
Plan water and input use together with expected yield and profitability, rather than looking at resource use in isolation.
Future Scope
Add multi-year data to check whether the seasonal patterns repeat.
Apply statistical tests to confirm that seasonal differences are meaningful.
Fix the State and District mismatches to make regional analysis reliable.
Explore machine learning models to predict yield and profit before a season begins.
Build a dashboard for farmers and planners.

