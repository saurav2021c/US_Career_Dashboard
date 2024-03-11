# US Career Dashboard
![Maven Career Dashboard](https://github.com/saurav2021c/US_Career_Dashboard/assets/97289683/191338e6-4090-4e1b-b3eb-ef12895ab830)

## High School Visit Dashboard - US Labor Statistics (2017-2020)

This **Excel** dashboard is designed to help high school seniors explore wage and employment trends across different industries throughout the United States, from 2017 to 2020. It provides an interactive tool to understand career options and salary expectations.


### [Portfolio Project](https://mavenanalytics.io/project/12900)

### Background Work:
![Background work1](https://github.com/saurav2021c/US_Career_Dashboard/assets/97289683/a3655175-015a-49f3-abd3-b66bee449740)

Let's break down the different sections of the table:

### 1. Industry Filter:
This section allows users to select a specific industry (e.g., Construction, Information, Finance) or see all industries ("All") combined. When an industry is selected, the data in the center and bottom sections of the dashboard will update to reflect that specific industry.

### 2. Avg Wage by Industry:
This section shows the average annual wage for each industry from 2017 to 2020. For example, in 2020, the average annual wage in the Information industry was $93,586.

### 3. Employees by Industry:
This section shows the total number of employees for each industry from 2017 to 2020. For example, in 2020, there were 26,277,342 employees in the Trade & Transportation industry.

### 4. Date Filter:
While not a table itself, this section allows users to filter the data by year. The image you sent only shows data for the year 2020, but the dashboard likely allows users to select other years between 2017 and 2020.

![Background work2](https://github.com/saurav2021c/US_Career_Dashboard/assets/97289683/d588d936-dbe9-47e0-90db-4addef3e4f06)

While the table itself doesn't show data by industry, the dashboard it likely belongs to does. By using a slicer (filter) on the dashboard, you can focus on a particular industry and see how the average wage and number of employees has changed within that industry over those four years.

---
### Dashboard Layout:

#### 1. Top Section:
- **Industry Slicer:** A drop-down menu allows users to focus on a particular industry or see all industries combined. There is no slicer for year based on the image you described.

#### 2. Center Section:
- **Wage and Employment Trends:** A bar chart displays both the average annual wage and the number of employees for each industry (Construction, Information, Finance, Business Services, Manufacturing, Natural Resources, Education & Health, Trade & Transportation, Other Services, Leisure & Hospitality) from 2017 to 2020. This allows users to see how wages and employment have changed within each industry over those four years.

#### 3. Bottom Section:
- **Map:** This section can be a choropleth map where each state is colored based on the average annual wage or total number of employees within the selected industry and year (depending on what you want to highlight).

### 4. Additional Considerations:
- **Dynamic Highlighting:** When a user selects a specific industry on the slicer, the corresponding line in both wage and employment trend charts can be dynamically highlighted for better focus.
- **State Details:** Include a small table that displays details for a chosen state on the map, such as industry name, average wage, and number of employees. This table can appear when a state is clicked on the map.
- **Data Protection:** Protect the underlying data sheet to prevent accidental modifications while allowing users to interact with the dashboard elements.

---
### Formulas Used:
- *SUMIFS:* This formula calculates the total number of employees based on specific criteria (Year and Industry).
- *AVERAGEIFS:* This formula calculates the average annual wage based on specific criteria (Year and Industry).

---
### Benefits for High School Students:
- Explore potential career paths based on industry trends.
- Understand the relationship between wages and experience (years since 2017).
- Gain insights into industries with high employment opportunities.
- Use the map feature to compare opportunities across different states.

This interactive dashboard provides valuable information for high school seniors as they make crucial decisions about their future careers.
