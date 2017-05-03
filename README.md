# 660B_project_Spring2017
Job Popularity Predictor
Project Done for web analytics class - Team No. 5

1. Run script.py code to scrape job application data from careerbuilder.com (Job name, Applicants, Date, Description)
- Number of Applicants and the date is scrapped in to traintest.csv file.
- Job Name is scrapped in to a text file.
- Description is Scarpped in to another text file.
- By importing the Job name text and descreiption text in to the traintest.csv, the entire data set is built.
2. Build Train and Test data sets:
- From the traintest.csv take 70% of data and build train.csv data set for training the machine learning algorithm.
- From the traintest.csv take the rest 30% data and build test.csv for testing it with the trained model.
3. Run ml.py (Predicting popularity of the jobs):
- Job Popularity prediction code, this predicts whether a job is popular in a scale of 1 to 5.
