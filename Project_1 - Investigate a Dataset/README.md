# Investigate a Dataset

##
I analyzed a dataset containing 14 features and 110,527 observations. The dataset is a collection of information from more than 100k medical appointments in Brazil and is focused on whether or not patients show up for their medical appointments. The analysis is focused on looking at the various factors that might have influenced the patients' decision to show up for their appointments or otherwise.

## Dataset

The data set used contains more than 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. It contains 14 features and 110,527 observations. The dependent variable is the "No-Show" feature and it contains two unique values - NO and YES. NO means the patient did show up for the appointment while YES means the patient didn't show up for the appointment. Further details can be found here

The features found in the dataset are:

+ PatientId - Unique ID number of the Patient
+ AppointmentID - Identification of each appointment
+ Gender - Male or Female
+ DataMaracaoConsulta - The day of the actual appointment, when they have to visit the doctor
+ DataAgendamento - The day someone called or registered the appointment, this is before appointment.
+ Age - How old the Patient is
+ Neighborhood - Where the appointment takes place
+ Scholarship - Whether or not the Patient is a benefiaciary of the social welfare program
+ Hypertension - Does the Patient have hypertension?
+ Diabetes - Is the Patient diabetic?
+ Alcoholism - Is the Patient a lover of alcohol?
+ Handcap - Is the Patient disabled?
+ SMS-Recieved - Did the Patient receive any SMS prior to the actual day of the appointment?
+ No-Show - Did the patient show or not?

## Conclusion

1. The number of those who show up and those who dont are relatively the same across both genders which means gender is not a very good predictor of whether people will show up or not
2. The analysis above suggests that apart from the children, who maybe are still being taken care of by their parents, people tend to show up as their age increases. The younger ones showed up the least while the older ones showed up more
3. Poor patients tend to not show up despite the scholarship which means the scholarship didn't really help.
4. Patients tend not to show up on weekends, while Monday, Tuesday, and Wednesday has the highest number of turnouts
5. The more the days pass by, the higher the tendency of patients not to show up. Most patients show up early
