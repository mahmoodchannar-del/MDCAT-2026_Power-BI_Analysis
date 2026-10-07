# MDCAT 2026 Candidate Performance Dashboard

This dashboard provides an interactive analysis of **MDCAT 2026 candidate performance** by tracking key metrics such as **Total Candidates, Qualified Candidates, Not Qualified Candidates, Qualification Rate, Average Marks, and Highest Marks**.

It also analyzes candidate performance across **districts, score ranges, and qualification status**, allowing users to identify differences in participation and performance across different areas.

The dashboard uses **DAX measures, interactive filtering, and district-level analysis** to make the results easier to explore and understand.

## 🔍 Key Features

- 📊 KPI cards for:
  - Total Candidates
  - Qualified Candidates
  - Not Qualified Candidates
  - Qualification Rate
  - Average Marks
  - Highest Marks
- 📍 Candidate analysis by district and area
- ✅ Qualified candidate analysis by district
- 📈 Qualification Rate comparison across districts
- 🎯 Candidate score distribution using score brackets
- 🟢 Qualified vs Not Qualified candidate comparison
- 📋 District-level score distribution matrix
- 🏆 Analysis of highest marks
- 🔎 Interactive filtering across dashboard visuals
- 🏙️ Grouping of Karachi districts for area-level analysis
- 📊 Detailed comparison of candidate volume and candidate performance

## 📈 Performance Analysis

The dashboard analyzes candidate performance using several different measures.

### Candidate Volume

Shows how many candidates appeared from each district or area.

This helps identify areas with the highest level of participation.

### Qualification Performance

Qualification Rate is used to compare candidate performance between districts.

This is important because a district with a large number of qualified candidates may simply have a larger candidate population.

Using **Qualification Rate** provides a fairer comparison between districts of different sizes.

### Score Distribution

Candidates are grouped into the following score ranges:

- Below 140
- 140–149
- 150–159
- 160–169
- 170–174
- 175–180

This makes it easier to understand how candidate performance is distributed rather than focusing only on the highest or average score.

## 🎯 Interactive Analysis

The dashboard allows users to interact with different visuals and explore specific areas of the data.

Users can analyze:

### District / Area

Allows users to focus on a particular district or area and examine its candidate performance.

### Qualification Status

Allows analysis of:

- Qualified Candidates
- Not Qualified Candidates

### Score Range

Allows users to explore candidates within specific score brackets.

When filters or visual selections are applied, the dashboard KPIs and charts update automatically.

## 📊 Dashboard Visuals

### Candidates by Area

A horizontal bar chart showing the number of candidates from each district or area.

### Qualification Rate by District

Compares the percentage of candidates who qualified across different districts.

### Candidate Score Distribution

Shows how candidates are distributed across different score brackets.

### Qualification Status

A donut chart showing the proportion of **Qualified** and **Not Qualified** candidates.

### Score Distribution by District

A matrix that compares score brackets across districts and provides a more detailed view of candidate performance.

## 🛠️ Data Preparation

The raw data was cleaned and transformed using **Power Query** before analysis.

The main preparation steps included:

- Cleaning and standardizing column values
- Correcting data types
- Checking missing and duplicate records
- Standardizing district names
- Merging the full MDCAT result dataset with the qualified candidate dataset
- Creating a `Qualification\_Status` field
- Creating score brackets
- Creating a score bracket sorting column
- Grouping Karachi districts for area-level analysis
- Preparing the final dataset for reporting

## 🧮 DAX Measures

DAX measures were created to calculate important dashboard KPIs, including:

- Total Candidates
- Qualified Candidates
- Not Qualified Candidates
- Qualification Rate
- Average Marks
- Highest Marks

These measures respond dynamically to filters and selections made on the dashboard.

## 📊 Analysis Covered

The dashboard provides insights into:

- Overall candidate participation
- Qualified and not qualified candidates
- Qualification percentage
- District-level performance
- Candidate distribution by area
- Score distribution
- Average candidate performance
- Highest candidate scores
- Performance differences between districts
- Candidate volume vs qualification performance

## 📅 Dataset

**Dataset:** MDCAT 2026 Candidate Results

**Total Candidates:** 33,336

**Qualified Candidates:** 19,323

**Not Qualified Candidates:** 14,013

**Overall Qualification Rate:** 57.96%

**Highest Score:** 179

The analysis combines the complete candidate result data with qualification information to create a single dataset for reporting and analysis.

## 💡 Key Analytical Insight

One important insight from this project is that **candidate volume and candidate performance are not the same thing**.

A district may have a large number of qualified candidates because it has a larger candidate population.

Therefore, metrics such as **Qualification Rate, Average Marks, and Score Distribution** provide a better comparison of performance between districts.

The dashboard allows these measures to be analyzed together instead of relying on only one KPI.

## 🎯 Project Objective

The objective of this project was to transform raw MDCAT candidate data into an interactive business intelligence dashboard while practicing:

- Data cleaning using **Power Query**
- Data transformation
- Data merging
- Data quality checking
- DAX calculations
- KPI development
- Score segmentation
- Interactive filtering
- Data visualization
- Dashboard design
- District-level analysis
- Business and analytical thinking

## 🛠️ Tools & Technologies

- **Microsoft Power BI**
- **Power Query**
- **DAX**
- **Excel / CSV**
- **GitHub**

---

**Data Analytics | Power BI | Power Query | DAX | Data Visualization**
