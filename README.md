# Data Science Projects Portfolio

## [Project 1: Movie Lens Collaborative Filtering Item-Based Recommender System](https://github.com/chelseako/ml_recommender_system)
* Created a collaborative filtering item-based recommender system application that prompts a new user to provide 20 ratings for movies they have seen, predicts the new user's ratings on unrated movies, and outputs the top N number of recommended unrated movies with the highest predicted ratings.
* System aids users in identifying content they are more likely to enjoy, providing a better user experience, and helps movie/tv/entertainment streaming companies attract and maintain customers, increasing revenue.
* Performed exploratory data analysis and data cleaning and preparation on the movies, ratings, users data.
* Compared the use of a standard estimator function and singular value decomposition (SVD) estimator function. Using a truncated matrix with the top 100 movies with the highest number of ratings, the standard estimator function produced a mean absolute error (MAE) of 0.769, while the SVD estimator produced an MAE of 0.787.
* Provided 20 real ratings using the standard and SVD estimator functions and found that the standard estimator produced 5 out of 10 recommended movies previously watched and enjoyed, while the SVD estimator produced 3 out of 10 movies previously watched and enjoyed. Thus, the standard estimator appears to be the better estimator.

![Percent Variance Explained](/Images/svd_components.png)

## [Project 2: Marketing Campaign Classification Project](https://github.com/chelseako/marketing_campaign)

* Built a classification model with 80% accuracy and an F1-score of 0.49 on the test data to predict customer acceptance of a marketing campaign.
* Identifying customers who are more likely to accept the campaign will assist companies in using their marketing resources more effectively, increasing overall profit.
* Cleaned and conducted data exploration on 2,240 observations and 29 columns (2 categorical, 1 date type, and the remaining 26 numerical) from https://www.kaggle.com/rodsaldanha/arketing-campaign.
* Compared model performance on a standardized original dataset and a standardized dataset that was balanced using Synthetic Minority Oversampling Technique (SMOTE) and Random Undersampling.
* Used GridSearchCV to identify the best parameters on seven different classification models.
* Compared nine different classification metrics, including an engineered profit metric.
* The two best models were selected and evalauted on the set aside test data. Results indicate the Random Forest Classifier produced the best overall metrics, including the highest profit score.

![Distributions of Variables](/Images/distributions.png)

## [Project 3: House Price Prediction Project](https://github.com/chelseako/House_Pricing_Project)
* Created a model that estimates sold prices for Honolulu houses (RMSE ~ $87,000) to help home buyers estimate a competitive bid offer.
* Custom built a web scraper using Python and Selenium for a local real estate website.
* Used only predictor variables that can be identified at time of listing.
* Cleaned 700+ observations of Honolulu houses sold within the past year using Python (Pandas, Numpy) and R.
* Optimized Linear, Ridge, Lasso, and Elastic Net Regressors to identify model with best predictive validity.

![Scatterplot of sold versus original price](/Images/scatter_sold_orig.png)

## [Project 4: FIFA 2019 Player Position Classifer](https://github.com/chelseako/FIFA_2019_Project)
* Created a linear discrimnant analysis (LDA) model that predicts player position (forward, midfielder, defender) with a cross-validated accuracy of 81%.
* Model can be used to assist club managers in determining what position best suits a player.
* Used principal component analysis (PCA) and factor analysis to reduce dimensionality and explore variable factoring.
* Identified five factors among numeric variables (overall, defending ability, size and movement, potential, and physical ability).
* As expected, the classifier had greater difficulty distinguishing between the midifielder and forward positions and the midfielder and defender positions, indicating greater overlap between midfielder and the other two positions.
* Club managers could potentially examine their midfield players' stats on the five factors to identify players that are more likely to be successful as a forward or defender, if those positions needed to be filled.

![3D Principal Component Analysis plot](/Images/3Dplot.png)
