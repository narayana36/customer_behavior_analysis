# customer_behavior_analysis

Project Overview
This project focuses on analyzing customer shopping behavior using transactional data containing around 3,900 records and 18 features. The objective is to understand customer spending patterns, product preferences, subscription behavior, and key business trends. The project follows a complete data analytics pipeline including Python-based data processing, MySQL analysis, Power BI visualization, and final reporting to support data-driven decision-making.

Step 1: Data Collection and Loading
The dataset was imported into Python using the Pandas library. Initial exploration was performed using functions like info() to understand data types and structure, and describe() to generate summary statistics. This step ensured a clear understanding of the dataset before further processing.

Step 2: Data Understanding and Exploration (EDA)
Exploratory Data Analysis was conducted to identify patterns and trends in the data. Customer demographics, purchase behavior, and product categories were analyzed. Visualizations such as bar charts, histograms, and count plots helped in understanding distributions like purchase amounts, frequency of purchases, and popular product categories.

Step 3: Data Cleaning
Data quality issues were handled in this step. Missing values in the review rating column were filled using median values based on product categories. Column names were standardized into snake_case format for consistency. Redundant columns such as promo_code_used were removed after checking duplication with discount_applied. Data types and inconsistencies were also validated and corrected.

Step 4: Feature Engineering
New features were created to enhance analysis. Customers were grouped into age categories such as young adult, middle-aged, and senior using binning techniques. A purchase frequency feature was derived to understand how often customers make purchases. These features improved segmentation and insights.

Step 5: Data Storage and MySQL Integration
After cleaning, the processed dataset was loaded into a relational database such as MySQL. This enabled efficient querying and structured analysis of business-related questions using MySQL.

Step 6: MySQL-Based Data Analysis
SQL queries were written to extract meaningful business insights. Analysis included revenue comparison by gender, identification of high-spending customers using discounts, top-rated products, and comparison of shipping types. Customer segmentation was performed to classify users into new, returning, and loyal categories. Additional queries focused on repeat buyers, top products per category, and revenue contribution by different age groups.

Step 7: Data Visualization (Power BI Dashboard)
An interactive dashboard was created in Power BI to visualize key insights. The dashboard included metrics such as total customers, average purchase amount, average ratings, revenue distribution, and customer segmentation. Visual elements like bar charts, pie charts, and filters allowed users to explore the data interactively.

Step 8: Insights and Business Recommendations
Key insights were derived from the analysis. Loyal customers contributed the highest share of revenue. Discount usage did not necessarily reduce spending, indicating strategic pricing opportunities. Certain products consistently showed high ratings and sales. Based on these insights, recommendations included improving subscription benefits, introducing loyalty programs, optimizing discount strategies, and focusing on high-performing products and customer segments.

Step 9: Reporting and Presentation
A detailed report was created summarizing the methodology, analysis, and insights. A presentation was built using Gamma to communicate findings in a clear and visually appealing manner for stakeholders and decision-makers.

Final Report
The final output of this project includes a cleaned and structured dataset, MySQL query results addressing key business questions, an interactive Power BI dashboard for visualization, and a detailed report with actionable insights and recommendations. Additionally, a presentation was created to effectively communicate the results to stakeholders. This end-to-end project showcases the ability to transform raw data into meaningful insights that support strategic decision-making.
