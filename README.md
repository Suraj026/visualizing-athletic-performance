## visualizing-athletic-performance
This mini project explores how data visualization can enhance the analysis of athletic performance and physical activity. By using real dataset, the project demonstrates how visual tools like line charts, heatmaps and bar chart etc. can uncover trends, highlight performance patterns, and provide actionable insights.

## Objectives
- Visualize key athletic metrics such as distance, pace, heart rate
- Explore relationships and patterns in running data
- Identify trends based on terrain, distance, and duration

## Dataset
Sample data includes:
- `Date`
- `Distance (km)`
- `Duration`
- `Average Pace`
- `Average Speed (km/h)`
- `Calories Burned`
- `Climb (m)`
- `Average Heart Rate (bpm)`
- `Terrain`
- 
>  File: `activity_data.csv`

## Tools & Libraries
- Python (Pandas, Numpy)
- Matplotlib & Seaborn
- Plotly
- Scikit-learn (for clustering)

## Visual Analysis & Key Insights

### 1. Correlation Analysis
A heatmap shows correlation between different performance metrics:
- **Distance and Duration** have strong positive correlation.
- **Climb and Average Heart Rate** are moderately correlated, indicating physical strain on hilly terrain.
- **Average Pace** is weakly negatively correlated with **Distance**, suggesting consistent pacing across sessions.

### 2. Pace vs. Distance by Terrain
Scatter plot analysis reveals:
- **Hilly routes** show a wider spread and higher pace values.
- **Flat terrains** allow for more consistent and faster pacing.
- **Mixed terrains** fall between the two, but closer to hilly routes in pacing distribution.

### 3. Activity Distribution and Range
From summary stats:
- Distance ranges from **0.76 km** to **49.18 km**
- Average Speed ranges from **1.04 km/h** to **24.33 km/h**
- Climb varies from **0 m** to nearly **1,000 m**, affecting effort levels

### 4. Heart Rate Trends
- The **average heart rate** is around **143 bpm**, with most values between **140–150 bpm**.
- High climb and longer distances are often associated with increased heart rate.


## Conclusion
This project demonstrates how visualizing fitness data helps in:
- Identifying how terrain affects pace and performance
- Understanding physical strain via heart rate and elevation
- Detecting training consistency and performance variations
