# MDCAT 2026 Candidate Performance Analysis

## Project Overview

This project analyzes MDCAT 2026 candidate performance using Power BI. The goal was to transform raw candidate-level data into an interactive dashboard that allows users to understand overall exam performance, qualification results, score distribution, and district-level differences.

The dataset contains 33,336 candidate records from different districts. I used Power Query for data cleaning and transformation, DAX for calculations, and Power BI visuals to present the results in a clear and interactive way.

The dashboard is designed to answer questions such as:

- How many candidates appeared in the exam?
- How many candidates qualified?
- What percentage of candidates qualified?
- Which districts had the highest number of candidates?
- Which districts performed better?
- How were candidates distributed across different score ranges?
- What were the average and highest marks?
- How did qualification performance vary between districts?

## Data Preparation

Before building the dashboard, I cleaned and transformed the data in Power Query.

The main preparation steps included:

- Correcting column data types
- Cleaning and standardizing district names
- Checking missing and duplicate values
- Merging the complete candidate dataset with the qualified-candidate dataset
- Creating a `Qualification_Status` field to classify candidates as Qualified or Not Qualified
- Creating score brackets for easier performance analysis
- Creating a district grouping field to combine Karachi districts where required
- Creating a sorting column so score ranges appear in the correct order

The main fields used in the analysis were:

- Seat No
- Candidate Name
- District
- District Group
- Obtained Marks
- Qualification Status
- Score Bracket

## Key Performance Indicators

The dashboard includes six main KPI cards.

### Total Candidates

This KPI shows the number of unique candidates included in the current analysis.

The full dataset contains **33,336 candidates**.

### Qualified Candidates

This KPI shows the number of candidates who met the qualification criteria.

It is calculated using the qualification status of each candidate.

### Not Qualified Candidates

This shows the number of candidates who did not meet the qualification criteria.

Comparing qualified and not qualified candidates helps show the overall level of exam performance.

### Qualification Rate

The Qualification Rate measures the percentage of candidates who qualified.

It is calculated as:

`Qualified Candidates / Total Candidates`

This is one of the most useful performance indicators because it allows qualification performance to be compared across districts, even when districts have very different numbers of candidates.

### Average Marks

This KPI shows the average score achieved by candidates in the current filter context.

It provides a broader measure of performance than simply looking at the highest score.

### Highest Marks

This KPI shows the maximum score achieved by a candidate.

Because the dashboard is interactive, the value changes when a particular district or group is selected.

## Dashboard Analysis

### 1. Candidates by Area

**Visual:** Horizontal Bar Chart

This chart compares the number of candidates across different districts or district groups.

It shows that candidate participation is not evenly distributed across all areas. Some areas, particularly Karachi, contribute a much larger number of candidates than many other districts.

This visual is useful for understanding candidate volume, but a high number of candidates should not automatically be interpreted as better performance.

### 2. Candidate Score Distribution

**Visual:** Column Chart

Candidates were divided into the following score ranges:

- Below 140
- 140–149
- 150–159
- 160–169
- 170–174
- 175–180

The chart shows how candidates are distributed across these score bands.

A large proportion of candidates are concentrated in the lower score range, while relatively few candidates achieved scores in the highest brackets.

This makes it easier to understand the overall score distribution instead of focusing only on the average or maximum score.

### 3. Qualification Rate by District

**Visual:** Horizontal Bar Chart

This chart compares qualification rates across districts.

Unlike candidate count, qualification rate allows districts of different sizes to be compared more fairly.

For example, a district may have fewer candidates but still achieve a relatively high qualification rate. Similarly, a district with a large number of candidates may not necessarily have the strongest qualification performance.

This distinction between **candidate volume** and **candidate performance** is important when interpreting the dashboard.

### 4. Qualification Status

**Visual:** Donut Chart

The donut chart compares candidates classified as:

- Qualified
- Not Qualified

It provides a quick overview of the proportion of candidates who successfully qualified.

The visual is connected to the rest of the dashboard, so the proportions automatically change when a district or score range is selected.

### 5. Score Distribution by District

**Visual:** Matrix

The matrix provides a more detailed breakdown of score ranges for every district.

Rows represent districts, while columns represent score brackets.

This makes it possible to compare not only the number of candidates in each district but also how those candidates are distributed across different performance levels.

For example, two districts may have similar candidate totals but very different numbers of candidates scoring above 160.

The matrix therefore provides a deeper level of analysis than the summary charts.

## Interactive Analysis

The dashboard was designed to be interactive.

When a user selects a district, score bracket, or chart element, the other visuals update automatically.

For example, selecting a district allows the user to immediately see:

- Total candidates in that district
- Qualified candidates
- Not qualified candidates
- Qualification rate
- Average marks
- Highest marks
- Score distribution

This allows the same dashboard to support both overall analysis and detailed district-level investigation.

## Key Insights

The analysis highlights several important patterns.

Candidate participation varies significantly between districts, with some areas contributing substantially more candidates than others.

The score distribution is heavily concentrated in the lower score ranges, while only a small proportion of candidates reach the highest score brackets.

Qualification performance also differs between districts. Therefore, candidate count alone should not be used to judge district performance.

Qualification Rate and Average Marks provide better measures for comparing performance between districts because they are less affected by the size of the candidate population.

The dashboard also shows the value of combining several KPIs. For example, a district may have a high number of qualified candidates simply because it has many total candidates, while another smaller district may actually have a better qualification rate.

## Business / Analytical Interpretation

The dashboard demonstrates an important analytical principle:

**Volume and performance are not the same thing.**

A district with the highest number of candidates does not necessarily have the highest qualification rate.

For meaningful comparison, decision-makers should consider several indicators together:

- Number of candidates
- Number of qualified candidates
- Qualification rate
- Average marks
- Score distribution
- Highest marks

Using these indicators together provides a more balanced understanding of candidate performance.

## Tools and Skills Used

- Power BI
- Power Query
- DAX
- Data Cleaning
- Data Transformation
- Data Modeling
- KPI Development
- Interactive Filtering
- Dashboard Design
- Data Visualization
- Business Analysis
- GitHub

## Dashboard Preview

![MDCAT 2026 Dashboard](screenshots/dashboard-overview.png)