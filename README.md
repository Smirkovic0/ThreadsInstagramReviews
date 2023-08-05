
## Project Summary

This project presents an analysis of a dataset containing reviews for the 'Threads' app. The dataset comprises 32,910 reviews, each characterized by the source (platform where the review was posted), review description, rating, and review date.

### Data

The dataset used in this project is the 'Threads Reviews' dataset, downloaded from Kaggle. It contains 32,910 reviews posted on different platforms. Each review in the dataset is described by the following attributes:

- **Source**: The platform where the review was posted (e.g., Google Play, App Store).
- **Review Description**: The text of the review.
- **Rating**: The rating given by the user, on a scale of 1 to 5.
- **Review Date**: The date and time when the review was posted.

### Analysis

The analysis of the dataset was performed using Python and involved two main steps: data loading and exploratory data analysis.

#### Data Loading

The data was loaded using the Pandas library in Python. The dataset did not contain any missing values, and the data types of the attributes were appropriate for analysis.

#### Exploratory Data Analysis

Exploratory data analysis was carried out to understand the distribution of review ratings, the distribution of review sources, and the relationship between review ratings and sentiment polarity.

- **Distribution of Ratings**: The distribution of review ratings was examined.
- **Distribution of Sources**: The distribution of sources where reviews were posted was analyzed.
- **Sentiment Polarity by Rating**: The relationship between review ratings and sentiment polarity was studied.

[Link to the full analysis](https://github.com/Smirkovic0/ThreadsInstagramReviews/blob/main/threads-dataset-analysis.ipynb)

### Conclusions
During the exploratory data analysis, a dataset composed of app reviews was thoroughly examined. The investigation encompassed the following key points:

- Analysis of Review Ratings: It was found that a large proportion of surveys received a score of 5, indicating a predominantly positive user response.

- Examination of Review Sources: Google Play was identified as the primary source from which the majority of the research was collected.

- Assessment of Sentiment: Consistency was observed between the sentiment inferred from the review text and the given ratings. More positive sentiments were associated with reviews having higher ratings, whereas more negative sentiments were reflected in reviews with lower ratings.

