# Social Media Usage and External Influences: A Data-Driven Analysis

## Project Overview
Over the next two months, I will analyze the relationship between my social media usage and various external factors, such as environmental conditions, daily routines, and major events. By examining elements like daylight length, sleep patterns, internet connectivity, daily satisfaction, weather conditions, air quality, busy schedules, and breaking news trends, I aim to uncover patterns that influence my digital behavior. This project will provide valuable insights into how external conditions shape social media engagement and offer strategies to reduce social media addiction while improving productivity and overall well-being.

The approach is straightforward: track my daily routines, correlate them with my social media usage, and identify key trends through statistical analysis and data visualization. This project will allow me to develop a structured, data-driven understanding of my digital habits and how they are impacted by my environment.

## Objectives

### Understand Behavioral Influences
- Explore how external factors such as weather, air quality, and major news events influence my social media usage patterns.

### Identify Key Drivers
- Determine which factors have the strongest impact on my digital habits and personal well-being.
- Provide data-driven recommendations to improve digital well-being.

### Optimize Social Media Usage
- Use insights from data analysis to develop strategies for reducing unnecessary social media usage and increasing daily efficiency.

### Apply Data Science Skills
- Utilize data science techniques learned in my course to perform real-world data collection, analysis, and visualization.

## Motivation

### Personal Growth
Understanding the external influences on my social media behavior will help me develop better digital habits, leading to improved focus and well-being.

### Scientific Approach
Rather than relying on assumptions, this project allows me to analyze my habits with concrete data, making informed adjustments based on measurable insights.

### Practical Application
Applying theoretical knowledge from data science to analyze real-world behavior enhances my analytical skills and ability to interpret complex datasets.

### Long-Term Impact
This study is not only about social media usage but also about leveraging data science to improve digital well-being, focus, and productivity in various aspects of life.

## Dataset

The dataset for this project consists of two months of daily records. I will track the following variables:

### Internal Data:
- **Date**: The specific day of the record.
- **Social Media Usage**:Time spent on specific apps (Instagram, TikTok, etc.).Collected via phone screen-time apps and computer screen-time tracking tools (minutes spent daily).
- **Sleep Duration**: Total sleep duration (hours), recorded through a smartphone sleep-tracking app.
- **Sleep Quality**: Difference from optimal sleep (7 hours).
- **Day Satisfaction**: Self-assessed rating of overall satisfaction (scale of 1–10).
- **Busy Schedule**: Logged through personal calendars, homework logs, and lesson schedules.

### External Data:
- **Daylight Length**: Retrieved from public APIs like the Sunrise-Sunset API.
- **Internet Speed/Connectivity**: Data from sources such as Ookla Speedtest or regional ISP reports.
- **Weather Conditions**: Data from APIs like OpenWeatherMap (temperature, precipitation, etc.).
- **Air Quality**: Manually recorded data from local environmental monitoring services.
- **Breaking News Trends**: Data from Google Trends or news aggregators measuring the volume of significant news events.

## Tools and Technologies

To conduct this analysis, I will use the following tools:
- **Python**: For data cleaning, preprocessing, and statistical analysis.
- **Pandas**: To manipulate and structure the dataset.
- **Matplotlib and Seaborn**: For data visualization (scatter plots, heatmaps, time series analysis).
- **SciPy**: For hypothesis testing and regression analysis.

## Analysis Plan

### Data Collection
- Import daily records from various sources into a structured Pandas DataFrame.
- Handle missing values and standardize data formats.

### Exploratory Data Analysis (EDA)
- Generate scatter plots, heatmaps, and time series graphs to identify patterns and correlations.
- Examples include:
  - Scatter plot of social media usage vs. daily satisfaction rating.
  - Heatmap showing correlations between social media usage, sleep quality, and busy schedules.
  - Time series analysis tracking social media usage over time against external factors.

### Hypothesis Testing
- **H₀**: External factors have no significant effect on social media usage.
- **Hₐ**: At least one external factor significantly impacts social media usage.
- Conduct correlation analysis and regression modeling to determine significant predictors.

### Trend Analysis
- Investigate how fluctuations in daily satisfaction, busy schedules, and major news trends impact social media usage.
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
- **Daily Satisfaction & Social Media**: Low satisfaction days might show a spike in social media engagement as a coping mechanism.
- **Busy Schedules**: A negative correlation may exist between high workload days and social media time.
- **News Trends & Usage Spikes**: Increased social media activity during major events could indicate heightened digital engagement driven by news consumption.

## Limitations and Future Work

### Limitations
- **Data Accuracy**: Self-reported ratings for sleep quality and daily satisfaction may introduce subjective bias.
- **External Data Variability**: Differences in data collection methods for weather, air quality, and internet connectivity may affect consistency.
- **Correlation vs. Causation**: This study primarily identifies correlations rather than causal relationships.
- **Single Participant**: The dataset represents only my behavior and may not be generalizable to a wider population.

### Future Work
- **Expand Sample Size**: Conduct a similar analysis with multiple participants for broader insights.
- **Advanced Modeling**: Utilize machine learning techniques to better predict social media engagement trends.
- **Controlled Experiments**: Test behavioral interventions, such as limiting social media access on low-satisfaction days, and analyze the results.
- **Longitudinal Study**: Extend the analysis beyond two months to capture seasonal and long-term trends.

## Conclusion
By the end of this project, I hope to answer the following questions:
- What external factors most strongly influence my social media usage?
- Can data-driven strategies help reduce unnecessary social media engagement?
- How do satisfaction levels and environmental conditions impact digital habits?
- How can these insights be applied to enhance productivity and well-being?

This project is about more than just social media—it’s about leveraging data science to make better lifestyle decisions. Understanding the numbers behind digital behavior can lead to improved focus, efficiency, and overall quality of life.

References

Google Trends API: Google Trends

OpenWeatherMap API: OpenWeatherMap

RescueTime API: RescueTime

This project is part of the DSA210 course at Sabancı University.



