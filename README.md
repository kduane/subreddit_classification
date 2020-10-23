## Project Outline

### Phase 1 - Problem Definition
    1.1 Goal is two-fold:
        1. Using [Pushshift's](https://github.com/pushshift/api) API, collect posts from two subreddits
        2. Use NLP to train a classifier on which subreddit a given post came from. This is a binary classification problem.
    1.2 Subreddit Selection
    1.3 Problem Statement
### Phase 2 - Data Gathering
    2.1 define functions to gather from reddit pushshift API
    2.2 gather 5_000 posts and titles from each of 2 subreddits
        - subreddit r/legaladvice
        - subreddit r/bestoflegaladvice
    2.3 data cleaning
    2.4 save data to CSV for EDA
### Phase 3 - Exploratory Data Analysis
    3.1 VADER Sentiment Analysis
    3.2 Word Count/Length Analysis
    3.3 Pipeline/Grid Search 
    3.4 Title Tags?  y/n?
        - Best of has common title tags (ie. LAOP)
    3.4 save to CSV
### Phase 4 - Modeling
    4.1 Train/Test/Split
    4.2 Logistic Regression
    4.3 K-Nearest Neighbors
    4.4 Multinomial Naive Bayes
    4.5 Random Forest
### Phase 5 - Model Analysis
    5.0 Baseline Score 
    5.1 Compare Accuracy Scores
    5.2 Compare AUC-ROC Curves
    5.3 Production Model Confusion Matrix
    5.4 Examining Misclassified Titles
### Phase 6 - Conclusions 
    6.0 Revisit 1.3 Problem Statement 
    6.1 Conclusions
    6.2 Recommendations for Further Research
    6.3 Credits/References
    
### Data Dictionary:
