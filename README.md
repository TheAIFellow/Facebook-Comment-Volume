# Facebook-Comment-Volume
### There is an enormous amount of data uploaded to Facebook every day. Therefore, there is an essential need to analyze this data for many purposes. In this paper, a deep analysis of Facebook comment volume prediction has been conducted to demonstrate the effect of the number of comments on marketing. The data used consists of 603,813 observations provided by Facebook. It includes fifty-three input attributes that have been used to predict the number of comments a post is going to have in the next H hours. Moreover, several Machine Learning techniques have been applied to analyze this considerable amount of data. For instance, Stepwise Linear Regression, Gradient Boosting, Neural Network, and Decision Tree models. Findings indicate that the Neural Network model outperformed the other models used in previous studies with the smallest error; when Stepwise Linear Regression is used as a variable selection for it. However, Additionally, one of the most crucial outcomes of this study is determining the most significant variables. Particularly, it was found that the publication day of the post, number of check-ins, shares or likes on the page, and the number of comments in the last 24 or 48 hours were the most important variables. These variables contribute to garnering more comments, which results in more viewers and higher profit for the marketer. The study concludes with some limitations and suggestions for future research.

## Feature:
* Likes
* Checkins
* Activity on post
* Category
* Taking about

## Steps:

* EDA/Feature analysis
* Data Preprocessing
* Machine Learning Models
* Evaluation Metrics

# **Conclusion**
---
* ### XGBoost performed best on our dataset with test adjusted R2 score of  0.73.
* ### Gradient Boosting and Random Forest also performed well compared other models.
* ### From feature importance plot of Random Forest, Gradient Boosting and XGBoosting we can conclude that most important features are CC2 (Comment count in last 24 hrs w.r.t to selected basetime)
Base Time/Date 
* ### Dataset was large, so unable to use grid-search to find the optimal hyperparameters. Model accuracy can be improved.

