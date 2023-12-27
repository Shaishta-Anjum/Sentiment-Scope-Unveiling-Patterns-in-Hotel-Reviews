# Sentiment Scope: Unveiling Patterns in Hotel Reviews

![Hotel](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/rhema-kallianpur-uocSnWMhnAs-unsplash.jpg?raw=true)

This comprehensive data analysis project focuses on an extensive dataset of hotel reviews, aiming to extract meaningful insights for strategic decision-making in the hospitality sector. Leveraging techniques such as sentiment analysis, geographical exploration, and temporal trends, the project uncovers valuable patterns in customer feedback. The entire analysis was conducted in Python, with the aid of Azure Machine Learning for sentiment analysis, in the collaborative environment of Google Colab.

**Key Objectives and Techniques:**
- **Data Cleaning and Preprocessing:** The raw dataset underwent thorough cleaning and preprocessing to ensure uniformity, rectify missing and suplicate values, and prepare the data for analysis.
- **Sentiment Analysis:** Utilizing Azure Machine Learning add-in in Excel, reviews were categorized into positive, negative, and neutral sentiments, providing a nuanced understanding of customer feedback.
- **Geographical Exploration:** Location-based patterns were investigated to identify regions with the highest concentration of reviews, offering insights into customer preferences and highlighting areas for potential business focus.
- **Temporal Trend Identification:** The temporal trends of reviews were analyzed to uncover patterns in customer sentiment over time, identifying peak periods of positive reviews and potential areas for improvement.

**Insights and Visualizations:**
1. **Positive Sentiment Dominates:**
   - **Conclusion:** The majority of reviews express positive sentiment, with approximately 49.89% positive reviews, 39.99% negative reviews, and 10.12% neutral reviews.
   - **Approach:** Used "Azure Machine-Learning" add-in in Excel for Sentiment Analysis of Reviews.
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/1%20(1).png?raw=true)

2. **USA Dominance:**
   - **Conclusion:** The United States of America (USA) stands out as the location with the highest number of reviews.
   - **Approach:** Extracted yearly insights by grouping the data based on the 'Location' column.
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/1%20(3).png?raw=true)

3. **2018 Positive Reviews Peak:**
   - **Conclusion:** The year 2018 witnessed a peak in the number of positive reviews, indicating a specific period of heightened customer satisfaction.
   - **Approach:** Conducted a temporal analysis by grouping reviews based on their publication date.
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/1%20(2).png?raw=true)

4. **Peak Review Month and Positive Sentiment:**
   - **Conclusion:** December 2018 emerges as a pivotal month, hosting the highest overall number of customer reviews and standing out as the month with the most positive reviews.
   - **Approach:** Combined temporal and sentiment analysis to identify the pivotal month.
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/1%20(5).png?raw=true)
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/1%20(7).png?raw=true)

5. **Review Length and Sentiment Correlation:**
   - **Conclusion:** Negative reviews tend to have a longer average length compared to neutral and positive reviews, suggesting that customers expressing dissatisfaction may provide more detailed feedback.
   - **Approach:** Utilized text analytics to calculate the average review length for each sentiment category.
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/Screenshot%202023-12-28%20004158.png?raw=true)

6. **Most Loved Location (USA):**
   - **Conclusion:** The United States emerges as the most loved location, with a notable concentration of positive reviews.
   - **Approach:** Identified the location with the highest number of positive reviews.
     ![Visualization](https://github.com/Shaishta-Anjum/Sentiment-Scope-Unveiling-Patterns-in-Hotel-Reviews/blob/main/Visualizations/1%20(6).png?raw=true)

**Tech Stack:**
- **Programming Language:** Python
- **Libraries:** Pandas, Matplotlib, Seaborn, Azure Machine Learning
- **Environment:** Google Colab

This project showcases the transformation of raw, heterogeneous data into actionable insights through a systematic approach, providing hotel industry professionals with a robust foundation for data-driven decision-making.
