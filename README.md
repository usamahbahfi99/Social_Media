# Social Media Data Analysis
## Project Description
This project aims to analyze social media data to evaluate interaction patterns, correlation between post text length and number of interactions, sentiment analysis, and activity distribution by platform. The data used in this project is social media data which includes information about posts, interactions, platforms, and user information. Using data analysis and visualization techniques, this project helps identify trends in social media activity, interaction patterns, as well as sentiment related to content.
## Project Objectives
1. Analyze the frequency of posts based on time of day.
2. Evaluate the correlation between the length of the post text and the number of interactions (likes, comments and shares).
3. Identify users with the greatest impact based on total interactions.
4. Conduct sentiment analysis to determine the sentiment category (positive, negative, or neutral).
5. Analyze post distribution by platform and engagement trends by platform.
## Project Steps
### Data Preparation
- Import data from CSV files and review the structure and information in the data.
- Changed the date format for the 'post_date' column to suit time analysis.
- Remove or handle missing values ​​if necessary.
### Post Frequency Analysis
- Calculates posting frequency based on hours of the day.
- Using barplot visualization to show the number of posts every hour.
### Correlation of Text Length and Interaction
- Calculate the length of the post text and the total number of interactions (likes, comments and shares).
- Create a scatter plot to see the relationship between the length of the post text and the number of interactions.
- Determine whether there is a significant correlation between text length and number of interactions.
### Users with the Highest Total Interactions
- Group data by user and calculate the total interactions for each user.
- Identify users with the highest total interactions.
- Use a barplot visualization to show the top 10 users with the highest total interactions.
### Sentiment Analysis
- Use TextBlob to analyze the sentiment of post texts.
- Categorize sentiment into positive, negative, or neutral based on polarity scores.
- Use a countplot visualization to show the distribution of sentiment categories.
- Use a pie chart visualization to show the percentage distribution of sentiment.
### Analysis by Platform
- Calculate the distribution of posts by platform (e.g., Facebook, Twitter, Instagram).
- Use a barplot to show the number of posts for each platform.
- Analyze interaction trends based on the hour of the day and the platform used.
- Use a barplot to show the average interactions per hour for each platform.
- Create a visualization for the average interactions based on 4-hour intervals and platform.
## Results and Findings
- **Posting Frequency**: The posting frequency is almost evenly distributed throughout the day, with the highest peaks at 3 PM and 10 PM. This indicates consistent activity throughout the day, with two peak activity periods in the afternoon and evening.
- **Correlation Between Text Length and Interaction**: The scatter plot shows no significant correlation between text length and the number of interactions. This indicates that text length is not a determining factor in increasing interactions.
- **Users with the Highest Total Interactions**: Users with the greatest impact have the highest total interactions, demonstrating a strong influence within the social media community.
- **Sentiment Analysis**: The sentiment distribution shows a significant percentage of neutral sentiment, with lower percentages of positive and negative sentiments.
- **Platform-Based Analysis**: The distribution of posts shows varying activity across different platforms. The average interactions per platform indicate differing interaction trends for each platform.

## Conclusion
This project provides valuable insights into social media activity patterns, the correlation between post text length and interactions, and sentiment analysis. These analysis results can be used by marketing or social media teams to optimize content strategies, identify influential users, and understand activity trends across various platforms. Additionally, this analysis helps in identifying the best times to post content.
