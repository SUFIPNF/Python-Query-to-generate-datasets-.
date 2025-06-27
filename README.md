# Python-Query-to-generate-datasets-.
This Query generates a random fake dataset of patients, hospitals, date of admission, date of discharge, medicines, billing info.
Install and import Pandas for creating Dataframes.
Install and import Faker to generate fake datasets.
Import timedelta to calculate time difference.
Change the num_of_hospitals, I have added only 5 hospitals.
Change the number of patients dataset to be created, I have added 100K patients.
Possible to make small changes like :
  1. Changing inputs of 'min_age' and 'max_age' to generate random date of births.
  2. Changing 'start_date' and 'end_date' of admission of patient as per your needs.
  3. Changing inputs of 'discharge_time' so that it generates dates corresponding to that admission dates.
  4. Can add or remove diagnoses as per your choice.
  5. Can change medicines in respective of the diagnose.
  6. Also possible to make changes in range of generated bills.

At the end all the datasets will converted to dataframes using pandas and saved as a '.csv' file.
