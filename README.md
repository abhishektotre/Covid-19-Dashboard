# Covid-19-Dashboard
## Project Overview
This project aims to create an interactive and insightful COVID-19 dashboard using Power BI. The dashboard provides an overview of the evolution of COVID-19 cases and deaths over time, identifies patterns and trends, and visualizes the data in various formats to facilitate analysis.

## Visualizations Created
Evolution of COVID-19 Cases and Deaths Over Time by Region

## Patterns and Trends Analysis

1.Weekly Moving Average of Cases and Deaths

2.Country-wise Cases Count

3.Map Chart to Visualize the Intensity of Cases

4.WHO Region and Country Hierarchy

## Detailed Thought Process
1. Evolution of COVID-19 Cases and Deaths Over Time by Region
Objective: To visualize the trend of COVID-19 cases and deaths over time across different regions.

Approach:

Line Chart: Chosen for its effectiveness in displaying trends over time.

Data Configuration: Dates on the X-axis and metrics (cases and deaths) on the Y-axis, with regions as the legend for differentiation.

Interaction: Added slicers for regions to enable user-specific analysis.

2. Identifying Patterns or Trends
Objective: To highlight significant patterns, such as spikes or declines in cases and deaths.

Approach:

Line Chart or Area Chart: To focus on particular time periods.

Annotations: To mark key events or trends, providing context to the visual data.

3. Weekly Moving Average of Cases and Deaths
Objective: To smooth out daily fluctuations and highlight longer-term trends.

Approach:

Measure Creation: Used DAX to calculate the 7-day moving averages for cases and deaths.

Line Chart: To plot these measures, providing a clear trend over time.

4. Country-wise Cases Count
Objective: To provide a comparative view of COVID-19 cases across different countries.

Approach:

Bar Chart: Ideal for comparing values across categories (countries).

Interaction: Enabled slicers for date and region filtering.

5. Adding a Monthly Filter
Objective: To allow users to analyze data on a monthly basis.

Approach:

Slicer: Configured to filter the data by month, adding a layer of interactivity to the dashboard.

6. Map Chart to Visualize the Intensity of Cases
Objective: To provide a geographical representation of COVID-19 case intensity.

Approach:

Map Visualization: Chosen for its effectiveness in showing geographic data.

Configuration: Used country/region as the location, cases as the size, and a color gradient to indicate severity.

7. Creating a Hierarchy of WHO Region and Country
Objective: To organize the data hierarchically for easier navigation and analysis.

Approach:

Hierarchy Creation: Structured the data with WHO Region as the parent and Country as the child.

8. Identify Most Affected WHO Regions
Objective: To identify and analyze the regions most affected by COVID-19.

Approach:

Tree Map or Matrix: Effective for displaying hierarchical data and identifying major regions affected.

Configuration: Utilized the hierarchy and added cases/deaths as values for visualization.

## Final Steps
Styling and Customization: Ensured all visuals are styled consistently for readability and aesthetics.

## Interactivity: Added slicers and filters to enable users to interact with the data dynamically.

## Dashboard Layout: Organized the visuals logically, ensuring a user-friendly and intuitive layout.

## Conclusion
This dashboard project leverages Power BI's capabilities to transform COVID-19 data into meaningful insights. The visualizations provide a comprehensive view of the pandemic's impact, facilitating analysis and decision-making.
