# Social Media Usage and External Influences: A Data-Driven Analysis

## Project Overview
Over the next two months, I will analyze the relationship between my social media usage and various external factors, such as environmental conditions, daily routines, financial habits, and major events. By examining elements like daylight length, sleep patterns, internet connectivity, weather conditions, air quality, busy schedules, breaking news trends, and daily budget, I aim to uncover patterns that influence my digital behavior. This project will provide valuable insights into how external conditions and financial habits shape social media engagement and offer strategies to reduce social media addiction while improving productivity and overall well-being.

The approach is straightforward: track my daily routines, correlate them with my social media usage, and identify key trends through statistical analysis and data visualization. This project will allow me to develop a structured, data-driven understanding of my digital habits and how they are impacted by my environment.

## Objectives

### Understand Behavioral Influences
- Explore how external factors such as weather, air quality, financial habits, and major news events influence my social media usage patterns.

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
- **Social Media Usage**: Collected via phone screen-time apps and computer screen-time tracking tools (minutes spent daily).
- **Sleep Duration**: Total sleep duration (hours), recorded through a smartphone sleep-tracking app.
- **Sleep Quality**: Sleep duration (hours). Difference from optimal sleep (7 hours).
- **Busy Schedule**: Logged through personal calendars, homework logs, and lesson schedules.
- **Daily Budget**: The amount of money spent and saved each day, tracked through budgeting apps or manually recorded logs.

### External Data:
- **Daylight Length**: Retrieved from public APIs such as the Sunrise-Sunset API.
- **Internet Speed/Connectivity**: Data from sources such as Ookla Speedtest and regional ISP reports.
- **Weather Conditions**: Data from APIs such as OpenWeatherMap (temperature, precipitation, etc.).
- **Air Quality**: Manually recorded data from local environmental monitoring services (IQAir).
- **Breaking News Trends**: Data from Google Trends measuring the volume of significant news events.

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
  - Heatmap showing correlations between social media usage, sleep quality, daily budget, and busy schedules.
  - Time series analysis tracking social media usage over time against external factors.

### Hypothesis Testing
- **Example Hypothesis:**
  - **H₀**: External factors and financial habits have no significant effect on social media usage.
  - **Hₐ**: At least one external factor or financial habit significantly impacts social media usage.
- Conduct correlation analysis and regression modeling to determine significant predictors.

### Trend Analysis
- Investigate how fluctuations in daily satisfaction, busy schedules, financial status, and major news trends impact social media usage.
- Analyze seasonal patterns, such as whether lower daylight hours contribute to increased social media engagement.
- Explore whether financial stress leads to increased or decreased social media engagement.

### Example Analysis
- **Sleep vs. Social Media Usage**: A scatter plot with sleep duration on the x-axis and social media usage on the y-axis could reveal whether shorter sleep durations correspond with increased social media engagement.
- **Busy Days vs. Social Media Time**: Comparing social media usage on busy vs. non-busy days may highlight the impact of schedule intensity.
- **Breaking News Events and Usage Spikes**: Time series analysis can be used to identify whether major news events lead to temporary increases in social media usage.
- **Daily Budget vs. Social Media Usage**: A scatter plot showing spending behavior and social media engagement to analyze if financial stress leads to excessive social media use.

## Findings and Potential Insights

Although the project is still in progress, potential findings may include:
- **Daylight Length & Usage**: Shorter daylight hours may correlate with increased social media usage due to spending more time indoors.
- **Sleep Patterns**: Poor sleep quality may be associated with excessive nighttime social media use.
- **Internet Connectivity**: Variability in internet speed may impact engagement levels.
- **Busy Schedules**: A negative correlation may exist between high workload days and social media time.
- **News Trends & Usage Spikes**: Increased social media activity during major events could indicate heightened digital engagement driven by news consumption.
- **Financial Status & Social Media Use**: Higher spending or financial stress might correlate with increased social media scrolling, possibly as a coping mechanism or distraction.

## Limitations and Future Work

### Limitations:
- **Short Observation Period**: Due to the small period of observation, significant changes in factors such as daylight length may not be evident.
- **Correlation vs. Causation**: This study primarily identifies correlations rather than causal relationships.
- **Single Participant**: The dataset represents only my behavior and may not be generalizable to a wider population.

### Future Work:
- Expand the dataset to include financial literacy and spending behavior as additional influencing factors.
- Conduct experiments testing behavioral interventions, such as budgeting strategies that limit social media distractions.
- Test the hypotheses on a larger population dataset to validate findings across different demographics and digital behaviors.
- Extend the study duration to capture seasonal variations and long-term patterns in social media usage.

## Conclusion
By incorporating financial tracking, this project will provide deeper insights into how financial stress and habits influence digital behavior, helping to improve financial awareness and digital well-being.

