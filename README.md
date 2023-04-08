# Appointment-Task
Appointment data are activities related to the Schedule day, appointment day, Age of people with different health issues that showed up and didn't show up .
## APPOINTMENT 

#### Introduction

Appointment data are activities related to the Schedule day, appointment day, Age of people with different health issues that showed up and didn't show up .

In this analysis, I will be answering few questions on about the appointments. Each record represents a single day of Appointment, and includes PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Alcoholism, Handcap, SMS_received, no_show, month, weekday, hour.

#### Data Validation

Before analysing, i made sure i performed thorough data validation and data wrangling to the dataset that was provided to me. Step by Step details of my Data validation process are well explained below:

The original data consist of 110,328 rows and 14 columns, namely; PatientId, AppointmentID, Gender, ScheduledDay, AppointmentDay, Age, Neighbourhood, Scholarship, Hipertension, Diabetes, Alcoholism, Handcap, SMS_received, no_show.

* I checked the entire columns,
* I checked for null values,
* I noticed one of the values in the Age column has a subtraction sign, so i removed it,
* I noticed that the vlaues in the handicap column is more than 0 and 1 so i removed any value >1,
* I changed column name No-show to no_show,
* I replaced the values in no_show colum from yes/no to present/absent,
* I converted the ScheduledDay and AppointmentDay datatype to datetime data type,
* I separated months,hours and weekday from the ScheduledDay,
* I replaced the values of weekday column.


#### Questions

* what's the ratio of people who misss/didn't miss the appointment?
* who didn't show up more often male or female?
* Most month for not showing up?
* Most hour for not showing up?
* Most weekday for not showing up?
* Age distribution of patients?


#### Exploratory Data Analysis (EDA)

* The ratio of people who misss/didn't miss the appointment 79.80 for present and 20.19 for absent.
* The Females didn't show up more often.
* The most month for not showing up is May.
* The most hour for not showing up is 7.
* The most weekday for not showing up is Tuesday.
* In the age distribution we have people of 0-20 years of age more.


#### Conclusion

According to my analysis it shows that female didn't show up more for their appointment and we have more people presnt than absent for their appoinment, People didn't really show up for their appoint in may.
