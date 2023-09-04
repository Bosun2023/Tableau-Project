# Final-Project-Tableau

## Project/Goals

In this Tableau project, the goal was to analyze wildlife strike data from the FAA Wildlife Strike Database. The project aimed to derive insights into temporal trends, geographic distribution, wildlife categories, timing of strikes, and impact severity. The ultimate objective was to create an informative and interactive dashboard to communicate these insights effectively.

## Process

### Step 1: Data Exploration

1. Connected to the FAA Wildlife Strike Database.
2. Identified data types, characteristics and cleaning of the dataset.
3. Explored columns, including temporal data, geographic coordinates, wildlife categories, impact severity, and cost information.

### Step 2: Visualization and Dashboard Creation

1. Created a series of visualizations to address key data questions.
2. Designed an interactive dashboard called "FAA Wildlife Strikes Insights" to present the findings.

## Results

For this project, I chose Option 2, which involved creating a dashboard. I used the FAA Wildlife Strikes dataset from 2000-2015.

Visualizations Created:

1. Temporal Trends Line Chart: To visualize changes in strike frequency over time, helping identify seasonal patterns and trends.
2. Geographic Distribution Map: To display the spatial distribution of wildlife strikes, facilitating the identification of geographic hotspots.
3. Wildlife Category Analysis Bar Chart: To explore the relationship between different wildlife (Animal) categories, strike occurrences, and associated costs.
4. Timing of Strikes Pie Chart: To provide an overview of strike times during the day, aiding in understanding when strikes are more likely to occur.
5. Impact of Strikes Stacked Bar Chart: To analyze the impact categories of strikes over discrete months, allowing for a deeper understanding of the effects of strikes over time.

Data Question (Option 2):

The main data question was to understand the patterns and trends in wildlife strikes. Specifically, I wanted to know how wildlife strikes vary over time, their geographic distribution, the involvement of different wildlife categories, the timing of strikes during the day, and the severity of their impact.

Handling Null Values:
To address null values in the 'When: Time of Day' column, I leveraged the 'Collision Date and Time' column. By applying logic-based categorization, I successfully mapped timestamps to 'When: Time of Day,' eliminating null values.

## Challenges 

Challenges faced during the project:

1. Handling discrete time data and mapping it to 'When: Time of Day.'
2. Integrating geographic data effectively to show the spatial distribution of strikes.
3. Ensuring user-friendliness and interactivity in the dashboard.

## Future Goals
If more time were available, the following enhancements and future goals could be pursued:

1. Explore advanced predictive analytics using machine learning models to forecast strike occurrences.
2. Conduct an in-depth cost-benefit analysis to assess the financial impact of wildlife strikes.
3. Investigate the effectiveness of wildlife strike mitigation measures and their impact on strike frequency and severity.
4. Further enhance the interactivity of the dashboard to allow users to drill down into specific regions or time periods for detailed analysis.
