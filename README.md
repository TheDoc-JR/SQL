# SQL
My first steps in SQL

HackerRank.com > Simply SQL - The Sequel > "Top Competitors" (Difficulty: Medium)

Julia just finished conducting a coding contest, and she needs your help assembling the leaderboard! 
Write a query to print the respective hacker_id and name of hackers who achieved full scores for more than one challenge. 
Order your output in descending order by the total number of challenges in which the hacker earned a full score. 
If more than one hacker received full scores in same number of challenges, then sort them by ascending hacker_id.

Hackers Table: ![image](https://user-images.githubusercontent.com/108229433/180602138-d1ae0aa8-7b21-4295-bec2-680237aba67e.png)


Difficulty Table: ![image](https://user-images.githubusercontent.com/108229433/180602159-71031e33-3f5a-4e31-a2c5-17a1872ffa2d.png)


Challenges Table: ![image](https://user-images.githubusercontent.com/108229433/180602172-801fd80c-1930-439e-8474-64de141d1e0e.png)


Submissions Table: ![image](https://user-images.githubusercontent.com/108229433/180602176-d1c0eccc-ac7a-4127-a65f-5ac934f5fff6.png)

# My solving path:
1- Create a new table with the total number of challenges grouped by hacker ID and name.

2- Modify the table so it can only show the total number of challenges with the highest score. 

3- Then select the hacker ID and name of hackers (from this new table) who achieved full scores for more than one challenge 
(sorted in descending order by the total number of challenges and then sorted by ascending hacker ID).
