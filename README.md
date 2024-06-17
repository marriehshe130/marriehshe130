Which social media platform has the highest average time spent by users?
SELECT platform, AVG(time_spent) AS avg_time_spent
FROM social_media_data
GROUP BY platform
ORDER BY avg_time_spent DESC
LIMIT 1;
Answer: This query will provide the social media platform with the highest average time spent by users.
What is the average time spent on social media by users in different age groups?
SELECT age_group, AVG(time_spent) AS avg_time_spent
FROM social_media_data
GROUP BY age_group
ORDER BY age_group;
Answer: This query will give us the average time spent on social media by users in each age group, allowing us to see how usage varies across different demographics.
