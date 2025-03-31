# Social Media Usage and External Influences: A Data-Driven Analysis

## Project Overview
I will analyze the relationship between my social media usage and various external factors, such as environmental conditions, daily routines, and major events. By examining elements like daylight length, sleep patterns, internet connectivity, weather conditions, air quality, busy schedules, and breaking news trends, I aim to uncover patterns that influence my digital behavior. 

This project will provide valuable insights into how external conditions shape social media engagement and offer strategies to reduce social media addiction while improving productivity and overall well-being.

The approach is straightforward: track my daily routines, correlate them with my social media usage, and identify key trends through statistical analysis and data visualization. This project will allow me to develop a structured, data-driven understanding of my digital habits and how they are impacted by my environment.

---

## Objectives

### Understand Behavioral Influences
- Explore how external factors such as weather, air quality, and major news events influence my social media usage patterns.

### Identify Key Drivers
- Determine which factors have the strongest impact on my digital habits and personal well-being.

### Optimize Social Media Usage
- Use insights from data analysis to develop strategies for reducing unnecessary social media usage and increasing daily efficiency.

### Apply Data Science Skills
- Utilize data science techniques learned in my course to perform real-world data collection, analysis, and visualization.

---

## Motivation

### Personal Growth
Understanding the external influences on my social media behavior will help me develop better digital habits, leading to improved focus and well-being.

### Scientific Approach
Rather than relying on assumptions, this project allows me to analyze my habits with concrete data, making informed adjustments based on measurable insights.

### Practical Application
Applying theoretical knowledge from data science to analyze real-world behavior enhances my analytical skills and ability to interpret complex datasets.

### Long-Term Impact
This study is not only about social media usage but also about leveraging data science to improve digital well-being, focus, and productivity in various aspects of life.

---

## Dataset

This project utilizes multiple datasets from various sources to analyze internal and external factors affecting daily life. Below are the dataset details, including their sources, dataset names, and the specific columns used.

### **1. Daylight Length**
- **Dataset Source:** [Sunrise-Sunset API](https://sunrisesunset.io/api/)  
- **Dataset Name:** `Sunlight Duration Dataset`  
- **Column Used:** `"day_length"`

**Explanation:**  
The Sunrise-Sunset API provides information about sunrise, sunset, and total daylight duration for a given location. In this project, I use the `"day_length"` column, which represents the total duration of daylight in hours and minutes. This data will be used to analyze how the length of daylight might influence sleep patterns and social media usage.

---

### **2. Internet Speed/Connectivity**
- **Dataset Source:** [Ookla Speedtest](https://www.speedtest.net/) or local ISP reports  
- **Dataset Name:** `Internet Speed Dataset`  
- **Columns Used:** `"download_speed"` (Mbps), `"upload_speed"` (Mbps), `"ping"` (ms)

**Explanation:**  
Internet speed is a crucial factor in daily digital activities. The Ookla Speedtest API provides real-time data on download speed, upload speed, and latency (ping).  
For this project:
- `"download_speed"` and `"upload_speed"` are used to analyze whether slower internet affects social media usage.
- `"ping"` (latency in milliseconds) is also considered to measure connection stability.

---

### **3. Weather Conditions**
- **Dataset Source:** [OpenWeatherMap API](https://openweathermap.org/api)  
- **Dataset Name:** `Weather Conditions Dataset`  
- **Columns Used:** `"temp"`, `"humidity"`, `"weather_description"`

**Explanation:**  
Weather can significantly impact daily routines, mood, and outdoor activities. This project collects:
- `"temp"` (temperature in Celsius) and `"humidity"` (percentage) to observe their correlation with social media usage.
- `"weather_description"` helps categorize general weather conditions.

---

### **4. Air Quality**
- **Dataset Source:** Local environmental monitoring services or [Air Quality Index API](https://aqicn.org/api/)  
- **Dataset Name:** `Air Quality Dataset`  
- **Columns Used:** `"AQI"` (Air Quality Index)

**Explanation:**  
Air quality can affect physical health and mental well-being. The Air Quality Index (AQI) and fine particulate matter levels (PM2.5 and PM10) are collected to examine potential impacts on sleep and activity levels.  
- The `"aqi"` column represents overall air quality (higher values indicate worse air quality).

---

### **5. Breaking News Trends**
- **Dataset Source:** [Google Trends](https://trends.google.com/trends/)  
- **Dataset Name:** `News Trends Dataset`  
- **Column Used:** `"search_volume"`

**Explanation:**  
Significant news events may influence mood, stress levels, and digital engagement. Data from Google Trends helps track the intensity of major news events.  
- The `"search_volume"` column quantifies the number of searches related to trending news topics, which can be correlated with changes in sleep quality and social media usage.

---

### **6. Social Media Usage**
- **Dataset Source:** Collected from smartphone screen-time tracking apps  
- **Dataset Name:** `Screen Time Dataset`  
- **Column Used:** `"social_media_minutes"`

**Explanation:**  
Screen-time tracking apps provide insights into daily social media usage.  
- The `"social_media_minutes"` column records the total time spent on social media each day.

---

### **7. Sleep Duration and Quality**
- **Dataset Source:** Collected from my daily records using a sleep tracking app.  
- **Dataset Name:** `Sleep Data Dataset`  
- **Columns Used:** `"sleep_duration"` (hours), `"sleep_quality"`

**Explanation:**  
Sleep tracking apps measure total sleep duration and quality.  
- The `"sleep_quality"` column represents the difference from optimal sleep (7 hours). Negative values indicate a sleep deficit.

---

### **8. Busy Schedule**
- **Dataset Source:** Personal calendars, homework logs, lesson schedules  
- **Dataset Name:** `Busy Schedule Dataset`  
- **Column Used:** `"busy_hours"`

**Explanation:**  
A busy schedule can impact social media usage and sleep.  
- The `"busy_hours"` column records the number of hours occupied by work, school, or other activities.

---

## Tools and Technologies

To conduct this analysis, I will use the following tools:
- **Python**: For data cleaning, preprocessing, and statistical analysis.
- **Pandas**: To manipulate and structure the dataset.
- **Matplotlib and Seaborn**: For data visualization (scatter plots, heatmaps, time series analysis).
- **SciPy**: For hypothesis testing and regression analysis.

## Analysis Plan

### Data Collection
- Import daily records from various sources into a structured Pandas DataFrame.

### Exploratory Data Analysis (EDA)
- Generate scatter plots, heatmaps, and time series graphs to identify patterns and correlations.
- Examples include:
  - Scatter plot of social media usage vs. daily satisfaction rating.
  - Heatmap showing correlations between social media usage, sleep quality, daily budget, and busy schedules.
  - Time series analysis tracking social media usage over time against external factors.

### Hypothesis Testing
- **Example Hypothesis:**
  - **H₀**: External factors and financial habits have no significant effect on social media usage.
  - **Hₐ**: At least one external factor or financial habit significantly impacts social media usage.
- Conduct correlation analysis and regression modeling to determine significant predictors.

### Trend Analysis
- Investigate how fluctuations in busy schedules, and major news trends impact social media usage.
- Analyze seasonal patterns, such as whether lower daylight hours contribute to increased social media engagement.


### Example Analysis
- **Sleep vs. Social Media Usage**: A scatter plot with sleep duration on the x-axis and social media usage on the y-axis could reveal whether shorter sleep durations correspond with increased social media engagement.
- **Busy Days vs. Social Media Time**: Comparing social media usage on busy vs. non-busy days may highlight the impact of schedule intensity.
- **Breaking News Events and Usage Spikes**: Time series analysis can be used to identify whether major news events lead to temporary increases in social media usage.

## Findings and Potential Insights

Although the project is still in progress, potential findings may include:
- **Daylight Length & Usage**: Shorter daylight hours may correlate with increased social media usage due to spending more time indoors.
- **Sleep Patterns**: Poor sleep quality may be associated with excessive nighttime social media use.
- **Internet Connectivity**: Variability in internet speed may impact engagement levels.
- **Busy Schedules**: A negative correlation may exist between high workload days and social media time.
- **News Trends & Usage Spikes**: Increased social media activity during major events could indicate heightened digital engagement driven by news consumption.


## Limitations and Future Work

### Limitations:
- **Short Observation Period**: Due to the small period of observation, significant changes in factors such as daylight length may not be evident.
- **Correlation vs. Causation**: This study primarily identifies correlations rather than causal relationships.
- **Single Participant**: The dataset represents only my behavior and may not be generalizable to a wider population.

### Future Work:
- Conduct experiments testing behavioral interventions, such as budgeting strategies that limit social media distractions.
- Test the hypotheses on a larger population dataset to validate findings across different demographics and digital behaviors.
- Extend the study duration to capture seasonal variations and long-term patterns in social media usage.

## Conclusion
This project will provide a structured, data-driven approach to understanding my social media habits and how external factors influence them. By leveraging data science techniques, I aim to develop actionable strategies to optimize digital well-being and productivity.

