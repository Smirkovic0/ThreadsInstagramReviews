
## Project Summary

This project presents an analysis of a dataset containing reviews for the 'Threads' app. The dataset comprises 32,910 reviews, each characterized by the source (platform where the review was posted), review description, rating, and review date.

### Data

The 'Threads Reviews' dataset, downloaded from Kaggle, serves as the basis for this project. It contains 32,910 reviews posted on different platforms. Each review in the dataset is described by the following attributes:

- **Source**: The platform where the review was posted (e.g., Google Play, App Store).
- **Review Description**: The text of the review.
- **Rating**: The rating given by the user, on a scale of 1 to 5.
- **Review Date**: The date and time when the review was posted.

#### Exploratory Data Analysis

The analysis of the dataset was performed using Python.
As the dataset was almost clean, with no missing values and a single duplicated row (which I removed), I proceeded directly to the exploratory data analysis stage.

Exploratory data analysis was carried out to understand the distribution of review ratings, the distribution of review sources, and the relationship between review ratings and sentiment polarity.

- [**Distribution of Ratings**](https://github.com/Smirkovic0/ThreadsInstagramReviews/blob/main/charts/Distribution%20of%20ratings.png)
- [**Distribution of Sources**](https://github.com/Smirkovic0/ThreadsInstagramReviews/blob/main/charts/Distribution%20of%20Sources.png)
- [**Sentiment Polarity by Rating**](https://github.com/Smirkovic0/ThreadsInstagramReviews/blob/main/charts/Sentiment%20Polarity%20by%20Rating.png)
- [**Word Frequency in Reviews**](https://github.com/Smirkovic0/ThreadsInstagramReviews/blob/main/charts/Word%20Frequency%20Analysis.png)



### Conclusions
During the exploratory data analysis, I thoroughly examined a dataset composed of app reviews. The investigation highlighted the following key points:

- Analysis of Review Ratings: I found that a large proportion of surveys received a score of 5, indicating a predominantly positive user response.

- Examination of Review Sources: Google Play was identified as the primary source from which the majority of the research was collected.

- Assessment of Sentiment: I observed consistency between the sentiment inferred from the review text and the given ratings. More positive sentiments were associated with reviews having higher ratings, whereas more negative sentiments were reflected in reviews with lower ratings.
  
[Link to the full analysis](https://github.com/Smirkovic0/ThreadsInstagramReviews/blob/main/threads-dataset-analysis.ipynb)

