# mobile-device-usage-analysis

# Mobile Device Usage and User Behavior Analysis

Hello, this is our final project for CS 210: Programming with Python at Parami University (December 2024). It was made by May Mon Thant and Min Thant Hein, under Professor Aye Hnin Khine.

## Project Description

These days almost everyone has a smartphone, and when people buy a new one they usually think about things like battery life, data usage and how many apps they can install. So we wanted to find out how people actually use their phones.

We used a dataset from Kaggle with 700 smartphone users. It has information about 5 phone models (iPhone 12, Google Pixel 5, OnePlus 9, Samsung Galaxy S21 and Xiaomi Mi 11), the operating system (Android or iOS), the user's age and gender, and how much they use their phone each day. We explored the data in Python to see if there are any patterns, and then gave some recommendations for phone companies.

Dataset: https://www.kaggle.com/datasets/valakhorasani/mobile-device-usage-and-user-behavior-dataset

## What We Used

- Python (in Google Colab)
- Pandas for reading, cleaning and grouping the data
- Matplotlib and Seaborn for the charts

## Questions We Tried to Answer

- Does the operating system affect the number of apps installed?
- What is behind battery drain? Screen time, app usage time, or both?
- Do males and females use different amounts of data?
- Do older and younger users have different screen time?
- Which phone model and operating system do users rate the highest?

## What We Found

- Out of 700 users, 554 use Android and 146 use iOS. More men use Android and more women use iOS.
- The more screen time and app usage time, the more battery drain. You can almost draw a straight line through it.
- iOS users install more apps on average, and iOS has a little more battery drain than Android.
- Males use a bit more data than females (943.98 MB/day vs 914.32 MB/day), but the difference is small.
- iPhone 12 got the highest average user rating, then OnePlus 9 and Samsung Galaxy S21.
- Users aged 30 and over have slightly more screen time than users under 30 (5.3 vs 5.2 hours per day).

One thing to keep in mind is that iPhone 12 is the only iOS phone in the dataset, so when we compare Android vs iOS, we are really comparing four Android phones to one iPhone.

## Files

- notebooks/mobile_usage_analysis.ipynb - our final analysis
- notebooks/exploratory_analysis_draft.ipynb - our early exploration
- report/Python_Final_Report.pdf - the written report

## How to Run It

1. Download user_behavior_dataset.csv from the Kaggle link above.
2. Open the notebook in Google Colab (or Jupyter).
3. Upload the CSV file and change the file path in the first cell if needed.
4. Run all the cells and you will see all the charts.

Thank you for checking out our project!






