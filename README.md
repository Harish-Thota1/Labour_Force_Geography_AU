# Labour_Force_Geography_AU

# Education and Employment Outcomes in Australia

## Project Overview

This project explores the **factors that influence education, skills, and training choices** of young people in Australia, specifically focusing on the impact of **geography**, **funding sources**, and **education levels** on their post-school study paths and employment outcomes. The analysis uses data from various sources including program enrollments, program completions, subject enrollments, and student demographics.

### Objectives

1. **Geography's Role**: Analyze how **location** (state/territory and remoteness region) influences students' educational and employment outcomes.
2. **Perception of Employment and Financial Outcomes**: Examine young people's perceptions of **employment and financial outcomes** based on their education level and funding sources.
3. **Value of Education**: Explore whether students perceive post-school education to be **worth the money** in both the short and long term.

---

## Data Sources

The following datasets are used in this analysis:
- **Program Enrollments**: Contains information on student enrollments in different programs, categorized by location, education level, and other demographics.
- **Program Completions**: Tracks students who completed their enrolled programs.
- **Subject Enrollments**: Details on subject-level enrollments.
- **Students**: Includes student demographics such as age group, country of birth, highest school level completed, and labour force status.

### Key Columns
- **State/territory of residence**: Geographic location of students.
- **Remoteness region**: Classification of areas as urban, regional, or remote.
- **Labour force status**: Indicates whether students are employed, unemployed, or not in the labour force.
- **Apprentice/trainee status**: Shows whether the student is an apprentice or trainee.
- **Level of education**: Highest level of education attained.
- **Highest funding source**: Funding received by the student (e.g., government-funded, self-funded).
- **SEIFA (IRSD)**: Socioeconomic index that measures financial disadvantage in the student’s area.
- **Total**: Number of students in each category for aggregation purposes.

---

## Analysis Breakdown

### 1. Does Geography/Location within Australia Play a Part?

**Key Question**: How do educational and employment outcomes vary across different **states/territories** and **remoteness regions**?

**Approach**:
- Created a **stacked bar chart** to visualize the distribution of **Labour force status** across different **states/territories** and **remoteness regions**.
- Used a **choropleth map** to visualize employment rates across geographic regions.

**Outcome**:
- Geographic differences in labour force outcomes were observed, with remote regions showing lower employment rates and higher levels of students not in the labour force.

### 2. What Are Young People's Thoughts on the Likely/Expected Employment and Financial Outcomes?

**Key Question**: How do students perceive employment and financial outcomes based on their **education level** and **funding source**?

**Approach**:
- Created a **stacked bar chart** to show the relationship between **highest funding source** and **labour force status**.
- Generated a **box plot** to explore the distribution of employment outcomes by education level.
- Used a **scatter plot** to examine the relationship between **socioeconomic status (SEIFA)** and employment outcomes.

**Outcome**:
- Students who were government-funded showed slightly higher employment rates.
- Employment outcomes varied significantly based on **education level**, with higher education levels generally correlating with better employment prospects.

### 3. Do Young People Perceive That Post-School Education Is Worth the Money?

**Key Question**: Is higher education seen as financially rewarding in terms of employment outcomes?

**Approach**:
- Generated a **line chart** to show how employment rates change based on **level of education**.
- Created a **pie chart** to represent the proportion of students in each education level who are employed, unemployed, or not in the labour force.

**Outcome**:
- Higher levels of education (e.g., Bachelor's degree, Master's degree) are associated with higher employment rates, suggesting that students with these degrees perceive education to be worth the investment.
