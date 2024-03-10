<img src="Firefly Podcast Reviews 94193.jpg" width="450" height="450">
<p style="font-family: San Francisco; font-size:2.75em;color:#0056D2; font-style:bold"> <br>Inferential Statistical Analysis of the Podcast Reviews</p>
<p style="font-family: San Francisco; font-size:2.75em;color:#0056D2; font-style:bold"> <br>Analysis  is presented in the COVID-19 data Analysis.ipynb notebook</p>
<br>

<a id="0"></a>
 ### [Table of Contents](0)
1. [Project Introduction](#1)      
1. [Preparation and Initial Inspection](#2)
    1. [Observations](#3) 
1. [Data Preparation and Cleaning](#4) 
1. [Exploratory Analysis](#5)     
    1. [Podcasts by Rating](#6) 
    1. [Sentiment Analysis](#7)
    1. [Statistical inference](#8)
1. [Summary and Suggestions](#12)     
    
    

#### [Notebook by Mažvydas Brikas](https://www.linkedin.com/in/mazvydas-brikas/)      <br>[Podcast Reviews Dashboard](https://lookerstudio.google.com/reporting/d3b50089-c400-4d61-9f94-29c31c4b2fd4)
# Project Introduction

The main objective of this project is to analyze the Podcast Reviews Dataset.
</p><br>Dataset Information:

2 million podcast reviews for 100k podcasts, updated monthly. This dataset is intended to aid in analysis of text feedback and review data.

</p><br>Requirements:

- Load the data using SQLite and Pandas.
- Perform exploratory data analysis. This should include creating statistical summaries and charts, testing for anomalies, checking for correlations and other relations between variables, and other EDA elements.
- Perform statistical inference. This should include defining the target population, forming multiple statistical hypotheses and constructing confidence intervals, setting the significance levels, and conducting z or t-tests for these hypotheses.
- Create a dashboard using Looker Studio or another BI tool, e.g. Tableau with at least three different types of charts.
- Provide clear explanations in your notebook. Your explanations should inform the reader what you are trying to achieve, what results did you get, and what these results mean.
- Provide suggestions about how your analysis can be improved.
 

</p><br>Objectives:

- Practice working with SQLite datasets.
- Practice performing EDA.
- Practice applying statistical inference procedures.
- Practice visualizing data with Matplotlib & Seaborn.
- Practice creating dashboards.
- Practice reading data, performing queries, and filtering data using SQL and Pandas.
 
<br>

You can download dataset from [Kaggle](https://www.kaggle.com/datasets/thoughtvector/podcastreviews/versions/28).

Looker Studio [Podcast Reviews Dashboard](https://lookerstudio.google.com/reporting/d3b50089-c400-4d61-9f94-29c31c4b2fd4).

**Summary**:

This project aimed to explore Podcast Reviews Dataset to understand listener sentiment and preferences across different podcast genres. Key findings:

1. **General Sentiment and Ratings:**
   - The analysis revealed that podcast reviews are generally positive, with an average sentiment score of 0.284 and an average rating of 4.56. This indicates that listeners tend to enjoy the content they choose to review, with a skew towards higher ratings.
   - Business and religion/spirituality emerged as the highest-rated categories, suggesting a strong listener interest in these genres.
   - Business podcasts showing particularly high sentiment scores, implying that content in these categories resonates well with their audiences.
   <br><br>
2. **Strong Correlation Between Ratings and Sentiment:**
   - A significant positive correlation (r = 0.938) between average ratings and sentiment scores across different podcast categories suggests that higher-rated podcasts are also spoken of more positively in reviews.
<br><br>
3. **Sentiment towards business and comedy podcasts:**
   - A t-test comparing sentiment scores between business and comedy podcasts revealed a significant difference, indicating that business podcasts are received more positively than comedy podcasts. The t-statistic was notably high, and the p-value was extremely low (practically zero), strongly suggesting that this finding is not due to chance.
<br><br>
5. **Technology Podcasts Analysis:**
   - A specific analysis of technology podcasts showed no significant difference in sentiment scores compared to the overall average sentiment. This suggests that technology podcasts, as a category, align well with general listener satisfaction levels.
<br><br>
6. **Outlier Analysis:**
   - The identification of 8,501 outliers based on sentiment scores highlighted a subset of reviews with significantly negative sentiment. Analysis of these outliers provided insights into potential areas for improvement, ranging from content-related issues to technical problems with podcast access.
 
<br><br>
**Suggestions:**

1. **Text Analysis:**
   - Perform text analysis on the review content to identify common themes or topics that drive positive or negative sentiment. This could help podcast creators tailor their content more effectively to audience preferences.
<br><br>
2. **Cross-Genre Comparison:**
   - Expand the comparative analysis to include more genres. Are there specific elements of content presentation or topic selection that consistently lead to higher sentiment scores across different genres
<br><br>
3. **Trends:**
   - Examine how sentiment scores and ratings evolve over time. Are there any trends or patterns that correlate with external events or podcast release schedules.
h to health discussions in workplaces, emphasizing both physical and mental well-being.
