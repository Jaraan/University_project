# University Data Analytics

## Objective
To analyze and visualize university-related data to derive meaningful insights into country-specific trends, university performance, and ranking criteria while showcasing advanced data cleaning, SQL querying, and visualization techniques.

---

## Dataset Overview
The dataset named "University" includes the following six sheets:
- **Country**: Contains country-specific details related to universities.
- **University**: Lists university names and associated metadata.
- **University Ranking Year**: Yearly ranking information for universities.
- **University Year**: Annual data for universities, such as enrollment figures.
- **Ranking Criteria**: Criteria used to evaluate and rank universities.
- **Ranking System**: Details of various ranking systems.

---

## Data Preparation

### Data Cleaning (Python):
- Removed duplicate records, standardized column names, and handled missing values.
- Converted data types to ensure consistency and accuracy.
- Created calculated fields to enhance data quality.

### Data Integration (SQL):
- Imported cleaned datasets into SQL using Python’s `create_engine` method.
- Established relationships between tables and ensured referential integrity.

### SQL Queries:
- Derived insights through advanced SQL queries.
- Created views for dynamic data exploration.
- Designed triggers for automatic data validation and logging.

---

## Data Visualization

### Tools Used
- Microsoft Excel
- Power BI

### Dashboards
- **Country Analysis**: Highlighted trends in the number of universities, female and international students, and staff distributions by country.
- **University Analysis**: Focused on university performance, the number of male, female, and international students, and staff by university.
- **Ranking Analysis**: Illustrated trends in ranking criteria and systems over time.

### Features
#### Calculated Fields in Excel:
- **Calculated:**
  - Number of female students using provided percentages.
  - Number of international students using provided percentages.
  - Number of male students by subtracting female students from total students.
  - Number of staff from student-to-staff ratios.
- **Enhanced Interactivity:**
  - Provided slicers and filters in Excel dashboards.

#### DAX in Power BI:
- **Calculated:**
  - Number of female students using provided percentages.
  - Number of international students using provided percentages.
  - Number of male students by subtracting female students from total students.
  - Number of staff from student-to-staff ratios.
- **Interactive Visuals:**
  - Added actions like bookmarks and page navigation for interactive exploration.
  - Included slicers and filters for dynamic exploration.

---

## Findings

### Country Analysis
- Identified top-performing countries based on the number of high-ranking universities.
- Highlighted countries with the highest diversity in international students.

### University Analysis
- Discovered trends in gender representation across universities.
- Analyzed performance of universities over the years.

### Ranking Analysis
- Examined changes in scores of ranking systems and criteria across years.
- Uncovered criteria contributing to university ranking systems.

---

## Conclusion
This project demonstrates expertise in data cleaning, SQL integration, and visualization using Power BI and Excel. The dashboards provide actionable insights into university trends, highlighting factors influencing their rankings and demographics.
```   

