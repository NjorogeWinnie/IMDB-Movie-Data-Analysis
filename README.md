# IMDB-Movie-Data-Analysis

# Introduction
This project seeks to analyse the IMDB dataset to advise Microsoft on the best types of films to create.

# Motivation
This project was done as part of an assessment for a Data Visualization Course

# Understanding
Microsoft sees all the big companies creating original video content and they want to get in on the fun. They have decided to create a new movie studio, but they don’t know anything about creating movies. You are charged with exploring what types of films are currently doing the best at the box office. You must then translate those findings into actionable insights that the head of Microsoft's new movie studio can use to help decide what type of films to create.

# Overview
This project visualizes IMDB trends over the past decades using various python libraries like matplotlib and seaborn. The visualizations explore popular and successful movie genres, the impact of ratings on movies' financial success and which studios are producing successful movies.

# Dataset
The data was sourced from IMDb.It includes movie titles, release years, genres, gross, ratings and runtimes.
Missing values were handled by removing incomplete rows

# Experimental Design
1. Business Understanding
2. Problem statement
3. Main goal
4. Specifying the objectives
5. Defining metric for success
6. Data preparation
7. Data cleaning
8. Feature engineering
9. EDA to answer specific objectives
10. Summary and Conclusion
11. Follow up questions

Detailed analysis of these steps can be found by following this link https://github.com/NjorogeWinnie/IMDB-Movie-Data-Analysis/blob/main/Winnie_Njoroge1.ipynb

Additionally, the presentation slides for this analysis can be found by following this link https://github.com/NjorogeWinnie/IMDB-Movie-Data-Analysis/blob/main/Winnie%20Njoroge%20EDA%20Final%20Project.pptx

# Technologies and Software Used
--Python 3 (Pandas, numpy, seaborn, matplotlib)
--Google Colab

# Summary of Analysis

## 1. Most Financially Successful Movie Genres:
<img width="610" height="581" alt="image" src="https://github.com/user-attachments/assets/e878f44c-7fb0-4032-bec3-dea287e82f34" />


  Drama, Comedy and Action are the most prevalent genres in this dataset.
 <img width="627" height="364" alt="image" src="https://github.com/user-attachments/assets/e888708a-ed34-4699-93d7-cd007d23e229" />

*   Adventure, Sci-Fi, and Animation genres demonstrate the highest median total gross revenue among the genres analysed. While Drama and Comedy are prevalent, their typical financial returns are significantly lower.
*   Based on this, we advise Microsoft to prioritize producing movies in Adventure, Sci-Fi, and Animation** genres to maximize their potential for high box office returns.

## 2. Impact of Ratings and Audience Engagement on Financial Success: 
  <img width="627" height="405" alt="image" src="https://github.com/user-attachments/assets/2e3114b5-6ad3-4b54-b7ac-fa4cd09aeee2" />

  From the above scatter plot, there is a weak positive trend.
There are high grossing movies with high ratings, while there are high grossing movies with average or below average ratings.
Conversely, there are movies with high ratings that did not achieve very high total gross.
  <img width="627" height="405" alt="image" src="https://github.com/user-attachments/assets/a53525a8-574f-4b09-8fc5-cf156961bdef" />

  The scatter plot above, shows a clearer positive trend than the rating vs. gross plot. As the number of votes increases, the total gross tends to increase.
There is a visible cluster of movies with lower votes and lower gross, and as you move to higher vote counts, the potential for higher total gross generally increases.

This suggests that movies that generate more audience engagement (indicated by a higher number of votes) are more likely to achieve higher box office revenues.

*   The number of audience votes is a better indicator of potential total gross revenue than the average rating. High ratings alone do not guarantee high box office success, but movies with higher audience engagement (more votes) tend to perform better financially.
*  Based on this, we advise Microsoft to focus on creating movies that generate significant **audience engagement and buzz**. Marketing and distribution strategies should prioritize reaching a wide audience and encouraging interaction.

## 3. Performance of Existing Studios: 
 <img width="627" height="311" alt="image" src="https://github.com/user-attachments/assets/a641f5b4-d422-41cb-9b3a-74575e3a758f" />
 <img width="627" height="308" alt="image" src="https://github.com/user-attachments/assets/709c7f6d-1965-40b1-afbe-4866867ee68d" />
 <img width="627" height="308" alt="image" src="https://github.com/user-attachments/assets/8ad1ba17-0375-4767-9d51-6f215756a476" />
 
*  Studios like HC, P/DW, and BV show high median total gross, indicating strong typical performance. The analysis of domestic and foreign gross distributions reveals that some studios excel in specific markets and have varying levels of consistency and potential for blockbusters.
*   Based on this, Microsoft can study and learn from the strategies of successful studios, particularly those with high median gross and consistent performance in target markets. This could inform decisions about genre focus, production scale, and potential talent acquisition or partnerships. Understanding the variability in earnings can also help Microsoft define its own risk tolerance and production goals (consistent earners vs. high-risk blockbusters).

## 4. Trends in Movie Performance:
<img width="627" height="405" alt="image" src="https://github.com/user-attachments/assets/4addc8de-a720-4ce1-b148-e38b9c09f8f1" />

 *  Median total gross has been relatively stable after an initial dip in 2011.

 <img width="627" height="397" alt="image" src="https://github.com/user-attachments/assets/4956b636-09c5-49b7-98f6-ea8b11d5bef1" />
 
 *  Median average ratings have also remained consistent.

<img width="627" height="395" alt="image" src="https://github.com/user-attachments/assets/fcc9bd6a-c24e-49ad-a5f9-19dd00da2e0a" />

 *  The the median number of audience votes has shown a clear downward trend from 2010 to 2018.
   
*   The declining trend in audience engagement (votes) is a significant factor. Microsoft needs to develop strategies to counteract this trend and ensure their movies capture audience attention and generate interaction in a competitive market. Simply producing movies may not be enough; focusing on unique concepts, effective marketing, and engaging content will be crucial.

# Conclusion
To enter the movie industry successfully, Microsoft should strategically focus on **high-grossing genres like Adventure, Sci-Fi, and Animation**. While striving for quality (good ratings), they must prioritize **generating strong audience engagement** as this correlates more closely with financial success.
Understanding the landscape of existing successful studios and the **trend of declining typical audience engagement** is vital for developing a competitive strategy that aims to stand out and capture market attention.


# Setup
The easiest way to run this code is to upload and run it in google colab. Alternatively , if you would like to run it on your local computer you should install jupyter notebook and import the above listed libraries to be able to run the code. The data is included in this repository. Kindly download the data and load it in the desired environment to be able to run the code efficiently.

# Contact Details
If you would like to contribute to this project (be it reporting a bug, correcting a code or proposing a new approach altogether) feel free to reach out. If you run into problems while running this code or need clarification on how to run this code feel free to reach out to me. contact details: Github: NjorogeWinnie
