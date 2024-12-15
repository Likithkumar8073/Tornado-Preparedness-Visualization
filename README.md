# Tornado Preparedness Visualization Project

## Overview
This project analyzes tornado data from the NOAA Storm Prediction Center and the National Weather Service to provide actionable insights into tornado patterns and impacts. The visualizations aim to help decision-makers, such as meteorologists and emergency planners, prioritize disaster preparedness and allocate resources effectively.

### **Big Idea**
Understanding the frequency and severity of tornadoes across different states can help decision-makers prioritize disaster preparedness and resource allocation.

---

## Data Description
- **Source**: NOAA Storm Prediction Center & National Weather Service.
- **Key Fields**:
  - **Date and Time**: Tornado occurrence timestamps.
  - **Location**: Includes state and latitude/longitude of start and end points.
  - **Severity Metrics**:
    - Magnitude (intensity of tornadoes).
    - Injuries and fatalities.
    - Estimated property damage (`loss`).
  - **Dimensions**: Tornado length (`len`) and width (`wid`).

- **Purpose**:
  - Analyze tornado patterns and impacts.
  - Support meteorologists in improving storm prediction models.
  - Help emergency planners develop targeted response strategies.

---

## Target Audience
- **Primary Users**:
  - Meteorologists and weather researchers.
  - Emergency management professionals.
- **Use Cases**:
  - Refining tornado prediction models.
  - Developing disaster response strategies.
  - Allocating resources to high-risk areas.

---

## Visualizations Created
1. **Statewise Tornado Analysis**:
   - A bar chart showing the total number of tornadoes in each state.
2. **Impact and Severity Mapping**:
   - Heatmaps of loss, injuries and fatalities by state with a toggle feature to switch between the three.
3. **Tornadoes Over Time**:
   - A line chart analyzing the total number of tornado spread accross 1960-2022 for entire US and for each state.
4. **Seasonality Analysis**:
   - A line chart showing tornado occurrences across months to identify peak tornado seasons.

---

## Tools and Technologies
- **Tableau**:
  - Used for creating interactive dashboards and visualizations.
  - Includes calculated fields, parameters, and user toggles for dynamic data exploration.
- **Data Format**:
  - CSV dataset containing tornado details.
  - Tableau workbook (`.twbx`) with pre-built dashboards.
- **Presentation Tool**:
  - PowerPoint presentation summarizing findings and visualizations.

---

## Repository Structure
```plaintext
Tornado-Preparedness-Visualization/
├── README.md                     # Project documentation
├── data/
│   └── tornados.csv              # Tornado dataset
├── visualizations/
│   └── Draft5.twbx               # Tableau workbook with dashboards
└── presentation/
    └── Presentation.pptx         # Project presentation

