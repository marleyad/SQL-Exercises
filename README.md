# SQL Project Summaries

## AB Testing
**Summary:**  
Analyzed user engagement and purchasing behavior for an eyewear company using SQL, focusing on survey completion rates and A/B testing for try-on options. The analysis identified a higher purchase rate for the 5-pair home try-on approach, providing actionable insights for sales strategies.

**Key SQL Skills:**
- **Data Exploration and Aggregation:** Used `GROUP BY` and `COUNT` functions to analyze survey data and identify patterns in question completion rates.
- **Data Integration:** Leveraged `LEFT JOIN` to combine data across multiple tables (`quiz`, `home_try_on`, `purchase`) to build a comprehensive dataset for A/B testing.
- **Subqueries and CTEs:** Utilized `WITH` clauses for structuring complex queries and simplifying repeated logic.
- **Conditional Logic and Filtering:** Applied `CASE` statements and `WHERE` clauses to filter and segment data, enhancing the clarity of insights.

## Climate Insights with Window Functions
**Project Summary:**  
Conducted an in-depth analysis of state-level climate data using SQL, focusing on temperature trends and variations over the years. The project utilized window functions to calculate running averages, identify temperature extremes, and rank yearly temperatures. Additionally, quartile and quintile analysis provided insights into broader climate patterns across states.

**Key SQL Skills:**
- **Window Functions:** Applied functions like `AVG`, `MIN`, `LAST_VALUE`, `LAG`, and `RANK` to analyze temperature trends and identify key metrics across states.
- **Data Segmentation and Ranking:** Used `NTILE` and `RANK` to categorize data into quartiles, quintiles, and ranks, offering a detailed understanding of temperature distributions.
- **Data Filtering and Aggregation:** Implemented `WHERE` clauses and aggregate functions to extract specific insights and organize data effectively.
- **Common Table Expressions (CTEs):** Utilized CTEs for breaking down complex queries, facilitating analysis like matching temperature values across years.

## Project Staffing and Personality Analysis
**Project Summary:**  
Analyzed employee assignments and project distribution using SQL to identify project engagement, staffing gaps, and personality type trends. The project also explored compatibility between employees and projects, helping inform team assignments based on personality insights.

**Key SQL Skills:**
- **Data Filtering and Aggregation:** Used `WHERE` clauses and aggregate functions to identify employees without current projects and projects with varying team sizes.
- **JOIN Operations:** Performed `JOIN` operations to correlate employee data with projects, facilitating analysis of team assignments and project selection.
- **Subqueries and CASE Statements:** Implemented subqueries and `CASE` statements for complex logic, such as matching employee personality types to identify compatibility counts.
- **Data Analysis and Insight Extraction:** Conducted analyses to determine the most and least engaged projects, common personality types, and how they relate to project selection.

## Subscription Churn Analysis
**Project Summary:**  
Analyzed subscription data to determine user activity, identify cancellation patterns, and calculate monthly churn rates for specific segments. By cross-referencing user data with specific time periods, the project provided insights into subscription retention and customer behavior.

**Key SQL Skills:**
- **Data Exploration:** Examined subscription data to identify active and canceled users, extracting key metrics like total user counts and subscription dates.
- **Temporary Tables and CTEs:** Created temporary tables using Common Table Expressions (CTEs) to segment data and facilitate advanced analysis, including calculating monthly churn rates.
- **Cross Joins and CASE Statements:** Used cross joins and `CASE` statements to segment users and determine their activity status within specified timeframes.
- **Churn Rate Calculation:** Computed churn rates for specific segments by aggregating cancellations and active subscriptions, providing valuable insights into customer retention trends.

## Tracking First and Last Touch Campaigns
**Project Summary:**  
Analyzed page visit data to understand user behavior and evaluate the effectiveness of marketing campaigns. By investigating first and last touches, distinct page interactions, and purchase conversions, the project provided insights into the performance of various `utm_campaigns` and guided recommendations for marketing strategies.

**Key SQL Skills:**
- **Data Exploration:** Assessed the `page_visits` table to identify distinct `utm_campaigns`, `utm_sources`, and page interactions, helping understand overall user navigation patterns.
- **Common Table Expressions (CTEs):** Utilized CTEs to calculate first and last touch points for users, segmenting data to analyze campaign performance in driving initial engagement and conversions.
- **Aggregations and Joins:** Leveraged aggregate functions and `JOIN` operations to count user interactions, determining which campaigns were most effective at both attracting users and leading to purchases.
- **Data-Driven Recommendations:** Provided strategic recommendations for marketing based on the performance of `utm_campaigns`, identifying high-performing campaigns and suggesting the discontinuation of low performers.
