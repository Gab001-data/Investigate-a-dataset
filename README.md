## Investigate a Dataset
In this project we navigate the different data analysis processes namely; posing questions, wrangling (data acquisition, assess quality and tidyness issues, cleaning), analysing data and communicating findings via visualisation. the dataset consist of 100k records of medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. A number of characteristics about the patient are included in each row including; ScheduledDay, location of facilities, Scholarship etc. the goal of this analysis is to determine factors for predicting if a patient will show up for their scheduled appointment.

## Project Dependencies
you will need an installation of python and the following liberaries;
```
* Pandas
* Numpy
* Matplotlib
* Seaborn
```
Check the [Jupyter Notebook](https://github.com/Gab001-data/Investigate-a-dataset/blob/main/Investigate_a_Dataset.ipynb) for a workthrough of the analytical process implemented in this project which include.
```
1. Import Libraries
2. Data acquision and import into pandas dataframe
3. Data assessement
4. Data cleaning
5. Exploratory analysis
6. Communicating insights
```

# Insights
## Distribution of Patients that show up for appointments

![Distribution of patients](https://github.com/Gab001-data/Investigate-a-dataset/blob/main/distribution_showup.png)

The histogram above show distributions of patients that show up for their appointments for different variables of hipertension, diabetes, alcoholism, handicap, sms_received and scholarship.
From the distribution above it can be seen that most patients that show up for appointment have no known case of a disease, do not suffer from alcoholism neither did they receive sms notification or have scholarship.
Also we see that more patients show up if they receive SMS communications from the medical facility. this is closely followed by hypertensive patients

## No-show weekday medical appointment
![No-show weekday](https://github.com/Gab001-data/Investigate-a-dataset/blob/main/No_show_weekday.png)

The figure above is a bar chart illustrating average no-show for appointments for each weekday. We use bar chart here for bivariant analysis to correlate weekday (categorical variable) and avg no-show (Quantitative variabel).
A higher number of No-Show was recorded if appointment day falls on a Friday or Saturday (Weekend).

## Patients age distribution
![patients age distribution](https://github.com/Gab001-data/Investigate-a-dataset/blob/main/Age_distribution.png)

The chart above shows the age distribution for patients in the dataset.
The average age of patients that show up for appointment is greater than avg age for patients that didn't show up.
More children (0-10) and middle aged (45-50) patients show up for appointments.

## Summary/Recommendations
The following insights were derived based on analysis result from the dataset.

- Medical facilities should send sms communications to patients regarding their appointments. as patients who receive sms are more likely to show up for their appointments as seen from analysis.
- Appointments should be fixed on weekdays rather than weekend as there is an increased probabilty of patients pulling a no-show for weekend appointments. though we don't have enough data to make decisive conclusions as to why more patients don't show up for weekend appointments
- Facility location can affect if a patient shows up for appointments or not. although this is dependent on other factors like if patients received sms from the facility or if patients that book appointments are hypertensive as these are two important factors that have been identified for patients that show up to their appointments but exploring these relationships is beyound the scope of this analysis.
- More children and middle aged patients tend to show up for their appointment.
- More woment tend to not show up compared to their male counterpart. but we couldn't establish a strong correlation between gender of patients and no-show as more women than men also booked for an appointment.

## Limitations
- This analysis results may not be wholistic as we only utilized univariate and bivariate visualizations to establish relationship between few of the variables per time.
- Also due to the numerious number of locations in the dataset only the top 10 with no-show was considered in our analysis of location and only the outlier location were we experienced a 100% no-show was analyzed.

## Relevant Links
- [Jupyter Notebook](https://github.com/Gab001-data/Investigate-a-dataset/blob/main/Investigate_a_Dataset.ipynb)
- [Linkedln](https://www.linkedin.com/in/gabriel-ogih-609a091a1/)
- [Twitter](https://twitter.com/dev_gabby)
- [Medium Article]()