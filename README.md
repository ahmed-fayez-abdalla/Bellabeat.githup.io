# Bellabeat Smart Devices Analysis






## Objective 

What is the key pain point? 

I have been asked to focus on one of Bellabeat’s products and analyze smart device data to gain insight into how consumers are using their smart devices.

This will help guide marketing strategy for the company.



### User story 

Urška Sršen, cofounder and Chief Creative Officer of Bellabeat, believes that analyzing smart device fitness data could help unlock new growth opportunities for the company.



### Problem

- Users struggle to maintain consistent wellness routines due to lack of personalized insights.

- Limited understanding of user activity, sleep, and calorie trends.

- Opportunity to enhance user engagement and retention by leveraging data-driven insights.



### Why this analysis ?

- To uncover trends in daily activity, sleep, and calorie burn patterns.

- To identify opportunities for improving Bellabeat’s product features.

- To provide actionable recommendations that align with user behavior and preferences.



## Data Source 

Data Collection

- This Data contains personal fitness tracker from thirty fitbit users.

- The data collected included minute-level output for physical activity, heart rate, and sleep monitoring. It includes information about daily activity and steps.



Data Storage

The data is sourced from Kaggle (CSV files), [see here to find it.]([https://www.kaggle.com/datasets/bhavyadhingra00020/top-100-social-media-influencers-2024-countrywise?resource=download](https://www.kaggle.com/datasets/arashnic/fitbit))



## Tools 


| Tool | Purpose |
| --- | --- |
| Excel | data storage and initial analysis |
| Python | Cleaning, exploring, analyzing and visualizing the data |
| GitHub | Hosting the project documentation and version control |



## Files Used

- dailyActivity_merged

- hourlyCalories_merged + hourlyIntensities_merged + hourlySteps_merged in one file

- sleepDay_merged



## Cleaning Datasets

- daily_activity Dataset

-- Removing 3 Columns (TrackerDistance, LoggedActivitiesDistance, SedentaryActiveDistance)

-- Changing Date Format


- hourly_data Dataset

-- Changing Date Format

-- Changing StepTotal Column Name


- sleep_day Dataset

-- Removing Duplicates

-- Changing Date Format



## Results

Correlation Between Calories and Steps

- The chart shows a positive correlation between total steps taken and calories burned.


- As users increase their step count, their calorie burn rises proportionally.


- The regression line highlights a clear trend, with most data points clustered around it, indicating consistency across users.


![Correlation Between Calories and Steps](assets/images/calories_vs_total_steps.PNG)





Active distance trend lines

- A noticeable decline in light active distance and high active distance is observed during weekends.


- This indicates that users tend to engage in less physical activity as the weekend approaches.


![Active distance trend lines](assets/images/light_active_line.PNG)


![Active distance trend lines](assets/images/moderatly_active_line.PNG)


![Active distance trend lines](assets/images/very_active_line.PNG)





Calorie burn trends across the day

- The graph shows that the majority of calorie burn occurs between 7 AM and 7 PM, reflecting typical active hours during the day. This aligns with user engagement in physical activities and daily routines during daylight hours.


![Active distance trend lines](assets/images/caolories_over_time.PNG)





Frequency of daily sleep patterns

- The frequency of sleep times shows that most users sleep once a day, indicating a regular sleep routine. Instances of sleeping twice a day are less common and sleeping three times a day is extremely rare.


![Active distance trend lines](assets/images/frequency_sleep_time.PNG)





Total sleep minutes over the month

- The total minutes of sleep over the month reveal that users tend to sleep more on weekends compared to weekdays. This trend suggests that users might use weekends to catch up on rest or enjoy longer sleep durations.


![Active distance trend lines](assets/images/mins_sleep_over_the_month.PNG)



## Disussion

Findings

- Calorie Burn Over Time (7 AM - 7 PM)

-- Most calories are burned during the daytime, between 7 AM and 7 PM, reflecting higher activity levels during this period.

- Frequency of Sleep Times

-- Most users sleep once per day, indicating a regular sleep routine.

-- Sleeping twice a day is less common, and three times a day is rare.

- Total Sleep Minutes Over the Month

-- Users sleep more on weekends compared to weekdays, showing a preference for longer rest periods during weekends.

- Activity Preferences

-- Users engage in light active distances more frequently, with high active distances being less common.

-- A noticeable decline in activity levels occurs during weekends.





Implications

- Calorie Burn Over Time (7 AM - 7 PM)

-- Bellabeat could introduce personalized activity reminders during non-peak hours (early morning or late evening) to encourage more balanced calorie burn throughout the day.

-- Highlight these trends in the app to help users plan their active hours effectively.

- Frequency of Sleep Times

-- Users with irregular sleep schedules could benefit from personalized sleep coaching or reminders for a consistent sleep routine.

-- Insights about rare multiple sleep instances could inspire educational content about healthy sleep habits.

- Total Sleep Minutes Over the Month

-- Encourage users to maintain consistent sleep durations throughout the week by promoting better weekday sleep hygiene.

-- Develop weekend sleep tips or challenges to maximize rest benefits while avoiding oversleeping.

- Activity Preferences

-- Promote features like weekend challenges or light activity recommendations to keep users engaged during weekends.



## Recommendations

- Leverage these insights to create more personalized, timely reminders for activity and sleep.

- Promote consistent sleep routines throughout the week, even during weekends.

- Encourage users to stay active during weekends through engaging features like activity challenges or reminders.


