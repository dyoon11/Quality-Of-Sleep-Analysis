# Quality of Sleep Research Dashboard

## Introduction
Sleep serves a variety of purposes for our cognitive and physical well-being. According to the National Institute of health, "getting inadequate sleep over time can raise your risk for chronic (long-term) health problems." [1]. Due to the importance of sleep in our every day lives, it is vital to understand what one can do to increase and maximize one's quality of sleep. 

## Purpose
The purpose of this synthetic research [2] is to show which factors in this dataset impact quality of sleep while also showcasing the power of data visualization through Tableau to uncover a data driven solution that will improve quality of sleep. The research consists of a artificial survey of 374 participants with an average age of 42. Inforamation regarding the stress level, heart rate, age, physical activity, sleep duration and etc. is available in this dataset (please refer to the Data Dictionary for a full list of the elements in this dataset).

### Dataset Information
**Please note:** this is a **synthetic** dataset available for public use in Kaggle.com for data manipulating/cleaning/learning puproses. I am using this dataset in order to showcase my data analysis capabilities and to highlight my ability to grasp the intricacies of a new and unrefined dataset to derive a specific and robust business/personal solution.

#### Data Dictionary:

##### Dataset Columns:
* Person ID: An identifier for each individual.
* Gender: The gender of the person (Male/Female).
* Age: The age of the person in years.
* Occupation: The occupation or profession of the person.
* Sleep Duration (hours): The number of hours the person sleeps per day.
* Quality of Sleep (scale: 1-10): A subjective rating of the quality of sleep, ranging from 1 to 10.
* Physical Activity Level (minutes/day): The number of minutes the person engages in physical activity daily.
* Stress Level (scale: 1-10): A subjective rating of the stress level experienced by the person, ranging from 1 to 10.
* BMI Category: The BMI category of the person (e.g., Underweight, Normal, Overweight).
* Blood Pressure (systolic/diastolic): The blood pressure measurement of the person, indicated as systolic pressure over diastolic pressure.
* Heart Rate (bpm): The resting heart rate of the person in beats per minute.
* Daily Steps: The number of steps the person takes per day.
* Sleep Disorder: The presence or absence of a sleep disorder in the person (None, Insomnia, Sleep Apnea).

## Analysis
After downloading/uploading the dataset to Tableau, it was important to uncover the elements and understand how each element correlates to quality of sleep. By running simple regression calculations in Tableau to find the sample correlation coeffieicnt (r), it was not difficult to find the elements that had the highest correlation to quality of sleep. 

### R-Coefficient
_definition: sample correlation coeffiecient (r) is a statistical measure of how much varation there is between a dependent variable and an independent variable_

Pearson correlation coefficient (r) value	Strength	Direction
Greater than .5	Strong	Positive
Between .3 and .5	Moderate	Positive
Between 0 and .3	Weak	Positive
0	None	None
Between 0 and –.3	Weak	Negative
Between –.3 and –.5	Moderate	Negative
Less than –.5	Strong	Negative

## Findings
Using the Trend Model capabilities in Tableau, we can see each element's correlation coefficient. **EXAMPLE:**
![image](https://github.com/dyoon11/Quality-Of-Sleep-Analysis/assets/147287123/fe3b80bc-9487-474e-a1ec-a4cc4e18ba09)

* **Stress Level** - strong negative correlation to the quality of sleep
* **Heart Rate** - moderate negative correlation to the quality of sleep
* **Age** - weak positive to the quality of sleep
* **Physical Activity** - strong postitive correlation to the quality of sleep
* **Sleep Duration** - strong positive correlation to the quality of sleep

That being said, it was found that the participants who had a longer sleep duration, engaged more in physical activity, and had lower stress levels had a better quality of sleep.

When looking furhter into the health of the participants, there is a strong positive correlation between healthy individuals and better sleep quality as seen in the chart bleow for both males and females.

![image](https://github.com/dyoon11/Quality-Of-Sleep-Analysis/assets/147287123/47812110-1075-4b8a-86dd-428250ee4f69)

It can also be said that there are certain occupations that have lower quality of sleep than others. For example, scientists and sales representatives (bootom 2) in this study usually report of having less quality of sleep compared to engineers or lawyers (top 2).

![image](https://github.com/dyoon11/Quality-Of-Sleep-Analysis/assets/147287123/4e723026-1549-43c2-badf-55336e04fcd2)

## Conclusions
After uncovering the data elements in this dataset, the research shows that by engaging in physical activity, increasing the sleep duration to 7-8 hours, and having a healthy body will improve on the quality of sleep. Furthermore, there is a strong negative correlation between stress levels and quality of sleep. Therefore, it is vital to lower stress levels before going to sleep to improve the quality of one's rest. 

### Limitations
There are certain limitations in this dataset that may hinder the results. For example, socioeconomic and geographic data would be useful in determining where stress is derived and how quality of sleep is determined. Geography can play a huge role in the sleeping patterns of individuals as there are may be weather conditions and cultural differences. 
  
## Dashboard

![image](https://github.com/dyoon11/Quality-Of-Sleep-Analysis/assets/147287123/18482a6b-c1d4-48e3-ab17-c016295f1b4e)

https://public.tableau.com/app/profile/daniel.yoon6581/viz/QualityofSleepResearchDashboard/Dashboard1?publish=yes

## References
* [1] National Institute of Health. 2022. https://www.nhlbi.nih.gov/health/sleep/why-sleep-important. (2024)
* [2] Tharmalingam Laksika. 2023. https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset/discussion. (2024)
