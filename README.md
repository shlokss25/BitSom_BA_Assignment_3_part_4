BITSOM_BA_2511721

# Student Performance Analysis

This assignment is about analyzing student marks data and trying to predict if a student will pass or fail.

## What I did

First I loaded the dataset using pandas and explored it a bit like checking shape, data types and summary stats. I also checked how many students passed and failed.

Then I calculated average marks for each subject and also found the student with highest overall score.

## Visualizations

I created different plots using matplotlib like:

* bar chart for average subject scores
* histogram for math marks
* scatter plot for study hours vs average score
* box plot for attendance
* line plot for math and science

After that I used seaborn also to create some plots. It felt easier for some graphs compared to matplotlib.

## Machine Learning

I used logistic regression to predict pass or fail.

Steps I followed:

* selected features and target
* split data into train and test
* scaled the data using StandardScaler
* trained the model
* checked accuracy

I also printed predictions for test data to see where model is right or wrong.

## Dataset

The dataset has marks in different subjects, attendance and study hours. It is small (only 15 rows), so results are not perfect but that's okay.

## How to run

1. Install libraries:
   pip install pandas matplotlib seaborn scikit-learn

2. Open the notebook and run all cells:
   part4_visualization_ml.ipynb

## Notes

* Since dataset is small, accuracy may not be high
* This assignment helped me understand full ML workflow

## Author

Shlok
