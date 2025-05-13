# Data-Professional-Survey-Dashboard

## Overview
This Power BI dashboard visualizes the results of a survey conducted among data professionals. The survey aimed to gather insights into various aspects of their roles, including demographics, career satisfaction, salary trends, and challenges in breaking into the data field.

The dashboard offers an interactive and comprehensive overview of the survey data, enabling stakeholders to identify trends and derive actionable insights.

---

## Key Features

### 1. **Country Representation**
- A tree map visualizes the distribution of survey participants by country.
- Highlights the top countries represented in the survey, including:
  - United States
  - India
  - Canada
  - Other regions

### 2. **Average Salary by Job Title**
- Bar chart displays the average salary for different job titles, such as:
  - Data Scientist
  - Data Engineer
  - Data Analyst
  - Database Developer
  - Other related roles
- Helps identify the earning potential of various positions within the data industry.

### 3. **Favorite Programming Language**
- Bar chart shows the favorite programming languages of data professionals, including:
  - Python (most popular)
  - R
  - SQL
  - JavaScript
  - Java
- Enables understanding of the technology stack preferences in the industry.

### 4. **Difficulty to Break into Data**
- Donut chart illustrates how participants rated the difficulty of entering the data field:
  - Very Easy
  - Easy
  - Neither Easy Nor Difficult
  - Difficult
  - Very Difficult
- Provides insights into the challenges faced by aspiring data professionals.

### 5. **Happiness Metrics**
- Gauges display average happiness ratings (on a scale of 1 to 10) for:
  - Salary (4.27)
  - Work/Life Balance (5.74)
- Helps determine overall career satisfaction among survey participants.

### 6. **Survey Demographics**
- Total number of survey participants: **630**
- Average age of participants: **29.87**
- Gender distribution and other demographic insights are captured in the raw dataset.

---

## Raw Dataset Columns
The raw dataset used to generate this dashboard includes the following columns:
- `Unique ID`: Unique identifier for each survey participant.
- `Email`: (Anonymized) email addresses of participants.
- `Date Taken (America/New_York)` and `Time Taken (America/New_York)`: Timestamp of survey completion.
- `Browser` and `OS`: Technical details of the platform used.
- `City` and `Country`: Geographic data of participants.
- `Referrer`: Source of the survey link.
- `Time Spent`: Total time taken to complete the survey.
- **Survey Questions:**
  - `Q1`: Current role/title.
  - `Q2`: Career switch into data field.
  - `Q3`: Current yearly salary in USD.
  - `Q4`: Industry of employment.
  - `Q5`: Favorite programming language.
  - `Q6`: Happiness metrics on various aspects (e.g., salary, management, learning opportunities).
  - `Q7`: Difficulty in breaking into the data field.
  - `Q8`: Most important factor when seeking a new job.
  - `Q9`: Gender.
  - `Q10`: Age.
  - `Q11`: Country of residence.
  - `Q12`: Highest level of education.
  - `Q13`: Ethnicity.

---

## Insights from the Dashboard
1. **Geographic Trends**:
   - The United States has the highest representation among survey participants.
   - Other notable countries include India and Canada.

2. **Salary Trends**:
   - Data Scientists and Data Engineers command higher average salaries compared to other roles.
   - Entry-level salaries (e.g., 0-40k USD) are common among newer professionals.

3. **Programming Language Preference**:
   - Python is the most widely used and preferred programming language.
   - R and SQL are also popular choices among data professionals.

4. **Career Challenges**:
   - A significant portion of participants found it "Difficult" or "Very Difficult" to break into the data field.

5. **Career Satisfaction**:
   - Work/Life Balance scores higher in happiness metrics compared to Salary satisfaction.

---

## Future Enhancements
- Add filters for additional demographics like gender, ethnicity, and education level.
- Include trend analysis over time (e.g., salary growth, industry shifts).
- Enhance interactivity with drill-through pages for each metric.
