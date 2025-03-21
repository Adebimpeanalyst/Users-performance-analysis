# Learning platform users performance analysis

#### Introduction:
In online learning platforms, tracking user performance is crucial for understanding engagement, effectiveness and overall outcomes.
This project aims to analyze user performance data from a learning site using SQL to gain insights into users activity, including top-performing users, accuracy in submission snd total points earned. 
By leveraging SQL queries, we can efficiently extract, filter, and aggregate data to identify key performance metrics that help improve the learning experience.

#### Dataset Overview:
The dataset consists of information about user submissions for an online learning platform. Each submission includes:
- User ID
- Question ID
- Points Earned
- Submission Timestamp
- Username

This data allows you to analyze user performance in terms of correct and incorrect submissions, total points earned, and daily/weekly activity.

#### Analysis:
Q1. List All Distinct Users and Their Stats
- Description: Return the user name, total submissions, and total points earned by each user.
- Expected Output: A list of users with their submission count and total points.
  ![image](https://github.com/user-attachments/assets/87e37b19-dbb3-4f02-94bc-d90ef224106b)
  
 Q2. Calculate the Daily Average Points for Each User
- Description: For each day, calculate the average points earned by each user.
- Expected Output: A report showing the average points per user for each day.
![image](https://github.com/user-attachments/assets/53986560-fce8-4f76-9d39-3c4cc31f769a)

Q3. Find the Top 3 Users with the Most Correct Submissions for Each Day
- Description: Identify the top 3 users with the most correct submissions for each day.
- Expected Output: A list of users and their correct submissions, ranked daily.
  ![image](https://github.com/user-attachments/assets/8257dcb4-1126-4ebc-b232-d7770397ceba)

Q4. Find the Top 5 Users with the Highest Number of Incorrect Submissions
- Description: Identify the top 5 users with the highest number of incorrect submissions.
- Expected Output: A list of users with the count of incorrect submissions.
  ![image](https://github.com/user-attachments/assets/4bcc137c-d183-4d77-9d1c-58c488cdc251)

Q5. Find the Top 10 Performers for Each Week
- Description: Identify the top 10 users with the highest total points earned each week.
- Expected Output: A report showing the top 10 users ranked by total points per week.
  ![image](https://github.com/user-attachments/assets/797aa84a-8e1e-46d7-a43c-60e1609202b2)

#### Conclusion:
By analyzing user performance data using SQL, we identified:
- The most active users based on submission counts.
- Top users with the highest correct and incorrect submissions.
- Total points earned per user, helping measure learning effectiveness.
- User accuracy rates, which can indicate understanding levels and areas needing improvement.
 
These insights can be used to personalize learning experiences, recognize top performers, and provide targeted support for struggling users.
