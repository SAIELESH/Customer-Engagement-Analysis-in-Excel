# Customer-Engagement-Analysis-in-Excel

# Case Description
In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included an XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits. Additionally, the company expanded its course library, covering a broader range of topics to provide students with a richer set of skills and attract a larger audience. These enhancements were anticipated to positively impact the student experience, create an effective strategy for customer engagement, and contribute to the company's success in the coming year. With this Customer Engagement Analysis in Excel project, the goal is to analyze whether the new additions to the platform have increased student engagement.

# Project files
During this Customer Engagement Analysis in Excel project, I'll analyze a dataset from the 365 company. It's important to note that personal user information has been masked to ensure privacy, and the database's volume has been reduced for practical reasons. Nevertheless, I consider this dataset to accurately represent the company’s operations—providing a realistic and relevant context for my analysis.

In addition, I consider the following information about the column values while working with the data:

- student_id – the unique identifier for each student in the dataset. The field contains IDs for students who used the 365 Data Science platform with free or paid accounts in Q4 2021 (October 1, 2021 – December 31, 2021, both included) and Q4 2022 (October 1, 2022 – December 31, 2022, both included).

- student_country – identifies the country of each student. The field provides information about students’ geographic location and can help analyze regional differences or conduct country-specific analyses.

- Paid – indicates whether a student had a paid account during the specified period. It is a binary variable, where '1' represents a paid account and '0' represents a free or unpaid account. It helps differentiate between students who have access to additional features or content through a paid subscription.

- minutes_watched_21 – represents the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2021.

- minutes_watched_22 – denotes the student’s engagement level, as expressed by the number of minutes a student has watched in Q4 2022.

The Excel file 'Engagement Project.xlsx' consists of four sheets: Task 1 and 2, Task 3, Task 4, and Task 5. Each sheet contains specific information regarding the project's tasks and corresponding data. I will use the data in these sheets to answer the questions that follow.

# Descriptive Statistics
# Task 1
In 2022, there were high expectations for the growth of the 365 company and increased student engagement based on the introduction of new website platform features. Some of these features included an XP system that enabled students to track their progress, level up, and earn rewards by completing various learning objectives. The platform also offered in-app coins that could be exchanged for special awards, a leaderboard where students could compete for top positions in different divisions, earning weekly rewards and advancing up the ladder, and streaks to motivate students to maintain consistent learning habits.

The first task is to provide insights into the relative engagement levels in Q4 2021 and Q4 2022. I will focus on low-engagement users (those who watched between 1 and 100 minutes in 2021). Low-engagement users often represent the most significant potential for growth. If 365 can find ways to increase its usage, it could significantly impact the overall use of the platform.

If there are repeated students who watched in Q4 2021 and Q4 2022, how does their engagement compare between the two periods? Computed the mean, median, and standard deviation for these groups. Is there a difference in engagement between paid and free-plan subscribers?

# Task 2
Please open the 'Engagement project.xlsx' file and navigate to the 'Task 1 and 2' sheet using Microsoft Excel. I calculated the skewness and kurtosis of students who watched content in Q4 2021 and Q4 2022. Considered paid and free-plan students. Does the result contradict the mean and median values previously obtained? 

# Confidence Intervals
# Task 3
Please open the 'Engagement project.xlsx' file and navigate to the 'Task 3 sheet using Microsoft Excel.

You will find information about two pairs of students:

Students who haven’t had a paid-plan subscription
Engaged in Q4 2021
Engaged in Q4 2022
Students who have been paid-plan subscribers
Engaged in Q4 2021
Engaged in Q4 2022

For each of the four groups, I determined the minute interval within which be 95% confident that a randomly selected individual will be situated.

I showed What conclusions did I draw about the students’ engagement in Q4 2021 and Q4 2022?

Tip: Used the z-statistic when performing calculations.

# Hypothesis Testing
# Task 4

Used the data in Task 4 of the ‘Engagement project.xlsx’ to solve the following task.

I wanted to reach a data-driven customer engagement decision on whether the platform’s new features contribute to the increase of minutes watched on the platform for both free-plan and paying students—i.e., the rise in student engagement in their study process. To do that, used hypothesis testing on both groups (free-plan and paying) for 2021 and 2022. 

Null hypotheses include the following:

The engagement (minutes watched) in Q4 2021 is higher than or equal to the one in Q4 2022 (μ1 ≥ μ2). I test free-plan and paying students separately.
Additionally, made the following assumptions:

For free-plan students, I performed a two-sample t-test assuming unequal variances.
For paying students, I conducted a two-sample t-test assuming unequal variances.
I Performed a two-sample f-test for variances to support the assumptions.

I showed what conclusions I drew from this test. Commented on the results of committing a Type I or Type II error in this study. Which one would result in higher costs for the company?

Tip: The degrees of freedom are calculated using the following formula for independent samples with unknown variances, which are assumed to be unequal:

Note: Assume that the degrees of freedom equal 8,229 and 40,836 for paid- and free-plan students, respectively.  

# Task 5

This task is determining whether the average number of minutes watched in the US is similar to that in India.

Understanding the differences in usage patterns can help in product localization. The platform might need to tailor its content, features, or user interface to better fit the preferences or needs of users in different regions.

I focused only on free-plan students in 2022. Used the Excel sheet Task 5 to perform calculations.

Null hypotheses include the following:

The engagement (minutes watched) in the US is higher than or equal to that in India (μ1 ≥ μ2). We test only free-plan students.
The engagement (minutes watched) in the US is lower than that in India (μ1 < μ2). We test only free-plan students.
Additionally, performed a two-sample t-test assuming unequal variances.

I showed what conclusion I drew from this test. Is the engagement in the US higher than that in India?

Tip: Note that the degrees of freedom are calculated using the following formula for independent samples with unknown variances which are assumed to be unequal: 

Note: Assume that the degrees of freedom are equal to 11,001.
