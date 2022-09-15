# Detailed Instructions From Your Instructor Team

The objective of this challenge is for you to perform data engineering on a csv file to change the datetype of a column in order to create time series graphs in Tableau. In addition you will create visualizations that show the differences bike checkout times for the type of user and gender throughout the day as a heatmap. Then you'll create a story in Tableau and write a report that describes the key outcomes of the NYC Citibike analysis.

## Deliverable 1: Change Trip Duration to a Datetime Format

For the first deliverable, we are asking you to crack open your Pandas and Python skills and knowledge to change the datatype of the "tripduration" column from an integer to datetime. 

You should not find the tasks in this challenge to be difficult. However, we have provided [starter code](./Resources/NYC_CitiBike_Challenge_starter_code.ipynb) that you should download into your bikesharing folder, and rename it `NYC_Citibike_Challenge.ipynb`. The starter code, has commented steps in the file where you will need to add code to complete this part of the challenge.

Some of you will try to convert the datatype in Tableau. This conversion will not create the elapsed time in hours and minutes that is needed for Deliverable 2. Some of you may try to use the calculated field option but we advise against this because we would like you to practice using your data engineering skills instead. Others might be familiar with using the `astype()` function to change a datatype. However, for this part of the challenge you will need to use the `pandas.to_datetime()` function. 

We have provided a GoogleFu tip and a short exercise in the **Hint** callout to help you convert an integer to datetime datatype. It is important that you use the right unit of time in the `unit=` parameter. 

After the conversion to a datetime datatype the "tripduration" column is the same as in this image.

![The conversion of the tripduration column to a datetime object.](./tripcolumn_datetime_datatype.png)

## Deliverable 2: Create Visualizations for the Trip Analysis

For the second deliverable, you will create five visualizations in Tableau. The first two visualizations will use the datetime datatype for the "tripduration" column to show the length time bikes are checked out for all riders and genders. Then, you'll create heatmaps that show how many trips are taken for all riders and genders by the hour for each day of the week, and display a breakdown by type of user and gender what days of the week a user will checkout a bike. 

The visualizations you'll be creating in this challenge haven't been taught in the module, so you may be a bit challenging. We have provided the steps in the order to create each visualization on Tableau version 2020.2.4.

## Deliverable 3: Create a Story and Report for the Final Presentation

For this deliverable you will need to create a Story in Tableau using the five visualizations you create in Deliverable 2 and two visualizations that you created in the module. Then, you'll provide a report in the repository README with all seven visualizations with a summary of each visualization. The report will contain three sections: an overview of the analysis, results, and summary.

**Overview of the analysis:** Explain the purpose of this analysis.

**Results:** Using the visualizations you have in your Tableau Story provide a summary of each visualization underneath the image. 

**Summary:**  Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

The README.md document should be in the home directory of your repository. All links should be working, and images should be formatted and displayed where appropriate.

## Submission

Make sure you upload the following to your bikesharing GitHub pages repository:

1. The `NYC_Citibike_Challenge.ipynb` file.
2. An updated README.md that has the written analysis with visualizations. Also, embed the Tableau Public link in the README.md file.

## Grading Rubric

The [Tableau Grading Rubric](./Resources/Module_14_Challenge_Grading_Rubric.pdf) is provided for you to use when grading your submissions.
