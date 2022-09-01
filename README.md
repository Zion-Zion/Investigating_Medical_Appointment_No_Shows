# Investigating_Medical_Appointment_No_Shows
---------------------------------------------

Across the world, most meetings beteen patients and health practicioners is usually done after scheduling an appointment. This dataset collects information from 100k medical appointments in Brazil and is focused on the question of whether or not patients show up for their appointment. Features of the patient are included in each row. The columns are:

- PatientId: Identification of a patient; unique to its owner.
- AppointmentID: Identification of an appointment
- Gender: Gender; either Male or Female
- ScheduledDay: Day appointment was made.
- AppointmentDay: Day to visit the doctor.
- Age: Age of the patient.
- Neighbourhood: Area where the patient stays
- Scholarship: If the patient is a recipient of the Bolsa Família social welfare program by the Government of Brazil.
- Hipertension: If the patient is hypertensive
- Diabetes: If the patient is diabetic.
- Alcoholism: If the patient is an alcoholic.
- Handcap: If the patient is physically challenged.
- SMS_received: If the patient got an SMS reminder before the Appointment Day
- No-show: If the patient showed up for the scheduled appointment or not. This is the most important feature in the dataset.

---------------------------------------
## Question(s) for Analysis
- What age of patients show up more for appointments and otherwise?
- What gender of patients show up more for appointments?
- Do scholarship beneficiaries tend to show up for appointments compared to those that are not beneficiaries?
- What is the gender distribution of scholarship recipients
- What days of the week are preferred by patients?
- Does SMS remnder affect patients' turn out?

---
## Conclusion
- The distribution of the gender in the dataset is highly skewed towards the female gender. Because of this, calculations around gender needed to be normalised for unbiased results.
- Majority of the patients that showed up or not are those between aged 0 and 2. This is because that age bracket take a high percent of the population (6.84% for 3 data points of 103 unique ages). But interestingly, adults in their fifties and early sixties are more inclined to show up for their appointment, while young adults between age 17 to 30 are more inclined to not show up for their appointment.
- For ages that are outliers, only the negative age was droped. The patients aged above 100 had heir records kept.
- Both males and females show similar tendency to show up for their appointments.
- The scholarship recipients value the scholarship. 8 in 10 tend to show up for their appointments. when compared to that of non recipients, it is slightly better.
- Females tend to be beneficiaries of the scholarship than guys.
- SMS reminders did not really fulfill their's purpose. Of 100 patients that did not receive a SMS, 83 showed up for their appointments, while for 100 that got reminders, only 72 showed up.
- Patients prefer Tuesdays and Wednesdays for their appointments. weekends are usually free.
- Hypertension seem rife among the sample. Steps should be taken to reduce the rate at which patients become hypertensive.
