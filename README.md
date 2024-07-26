# Accident Data Analysis #

### Introduction ###

The analysis aims to uncover patterns in traffic accidents related to road conditions, weather conditions, and time of day using the provided traffic accident dataset. Additionally, it involves visualizing accident hotspots and examining contributing factors to better understand the data and identify key insights.

**1. Analyzing Patterns Related to Road Conditions, Weather, and Time of Day**

- **Road Surface Conditions:** The analysis of accidents by road surface conditions is performed using a count plot, which reveals the distribution of accidents across different road surface types.

- **Weather Conditions:** Accidents are analyzed by weather conditions using a count plot to understand how different weather conditions impact accident frequency.

- **Time of Day:** The dataset is examined to identify accident patterns throughout the day by extracting the hour from the 'Time' column and visualizing accident counts per hour using a count plot.

**2. Visualizing Accident Hotspots**

- **Heatmap of Accident Hotspots:** A geographical heatmap is created using `folium` to visualize accident hotspots. This map is centered on the mean latitude and longitude of the dataset and uses a heatmap layer to highlight areas with high accident frequencies.

**3. Additional Analysis**

- **Accidents by Day of the Week:** A count plot is used to analyze accidents by day of the week, providing insights into which days experience more accidents.

- **Accidents by Junction Control:** The impact of junction control types on accident frequency is explored using a count plot.

- **Accidents by Accident Severity:** The dataset is examined to understand how accident severity varies using a count plot.

### Results ###

The analysis provides insights into how road conditions, weather, and time of day influence accident occurrences. The heatmap visualization identifies high-risk areas for accidents, while additional plots help in understanding patterns related to the day of the week, junction control, and accident severity.

