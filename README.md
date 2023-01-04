# School_District_Analysis

Deliverable 1: Collect the Data
Import the data from the new_full_student_data.csv file into a DataFrame named student_df by using the Pandas read_csv function and the os module.

Confirm that Pandas correctly imported the data by using the head function, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483386-7d795770-c230-4d52-b295-04bab5178f48.png)

Deliverable 2: Prepare the Data
In the student DataFrame, check for rows that have NaN (or missing) values, and remove those rows, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483407-5f3170a3-ff2b-4b2a-be9a-7096600ebaad.png)

In the student DataFrame, check for duplicate rows, and remove them.

Check the data types of the columns by using the dtypes property, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483434-fce0da55-18a9-4bef-b297-6f85388b0a07.png)

In the grade column, remove the "th" suffix from every value by using str and replace, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483457-645a9ccf-2c6f-4a12-996e-757f815331c1.png)

Change the "grade" column to the int type, and then verify the column types, as the following image shows:

A![image](https://user-images.githubusercontent.com/117414960/210483470-78c02fdc-9947-4d7f-80eb-39f29aae84ad.png)

Deliverable 3: Summarize the Data
Generate the summary statistics for the student DataFrame by using the describe function, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483492-824edf37-9942-4390-8ac9-0e48c5a24554.png)

Display the mean math score by using the mean function.

Store the minimum reading score in min_reading_score.

Deliverable 4: Drill Down into the Data

Display the grade column by using loc, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483530-6b6a6e88-1199-49ba-ac83-6f5aa6b29cf2.png)

Display the first three rows of Columns 3, 4, and 5 by using iloc, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483540-3aafd45b-1404-40cd-82b1-5475119952a7.png)

Select the rows for Grade 9, and display their summary statistics by using loc and describe, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483643-cb7c3a3b-7e9b-48b0-8bef-216d39a61f0d.png)
Store the row with the minimum overall reading score in min_reading_row by using loc and the min_reading_score variable from Deliverable 3, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483668-c525c644-76ff-462a-9189-64a0f7baf039.png)

Select all the reading scores from the 10th graders at Dixon High School by using loc with conditionals, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483694-d824a58a-c712-483f-ae7c-227b4a6432e8.png)

Find the mean reading score for all the students in Grades 11 and 12 combined by using conditional statements and loc or iloc.

Deliverable 5: Compare the Data
Display the average budget for each school type by using the groupby and mean functions, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483712-6156a08c-fe5b-4e76-b2c5-5206cb216f86.png)

Find the total number of students at each school, and sort those numbers from largest to smallest by using the groupby, count, and sort_values functions, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483721-1aa5b5fa-7846-48a8-876c-08fcf3b36887.png)

Find the average math score by grade for each school type by using the groupby and mean functions, as the following image shows:

![image](https://user-images.githubusercontent.com/117414960/210483737-9d9e8b98-2f65-4def-ad29-c2a37bcd6e43.png)

Deliverable 6: Report Findings
Using the provided cell, write a brief summary of your findings as follows: Write a few sentences to describe any discoveries that you made while performing your analysis. Include any additional analysis that you believe would be worthwhile.
