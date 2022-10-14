## [Project 1: Marketing Campaign Classification Project](https://github.com/chelseako/marketing_campaign)

* Built a classification model with 80% accuracy and an F1-score of 0.49 on the test data to predict customer acceptance of a marketing campaign.
* Identifying customers who are more likely to accept the campaign will assist companies in using their marketing resources more effectively, increasing overall profit.
* Cleaned and conducted data exploration on 2,240 observations and 29 columns (2 categorical, 1 date type, and the remaining 26 numerical) from https://www.kaggle.com/rodsaldanha/arketing-campaign.
* Compared model performance on a standardized original dataset and a standardized dataset that was balanced using Synthetic Minority Oversampling Technique (SMOTE) and Random Undersampling.
* Used GridSearchCV to identify the best parameters on seven different classification models.
* Compared nine different classification metrics, including an engineered profit metric.
* The two best models were selected and evalauted on the set aside test data. Results indicate the Random Forest Classifier produced the best overall metrics, including the highest profit score.

![Distributions of Variables](/Images/distributions.png)

## [Project 2: House Price Prediction Project](https://github.com/chelseako/House_Pricing_Project)
* Created a model that estimates sold prices for Honolulu houses (RMSE ~ $87,000) to help home buyers estimate a competitive bid offer.
* Custom built a web scraper using Python and Selenium for a local real estate website.
* Used only predictor variables that can be identified at time of listing.
* Cleaned 700+ observations of Honolulu houses sold within the past year using Python (Pandas, Numpy) and R.
* Optimized Linear, Ridge, Lasso, and Elastic Net Regressors to identify model with best predictive validity.

![Scatterplot of sold versus original price](/Images/scatter_sold_orig.png)

## [Project 3: DREAM Project](https://github.com/chelseako/DREAMProject)
* Selected by the Master's of Science in Computer Science (MSCS) Consortium to participate in the Distributed REsearch Apprenticeships for Master's (DREAM) Program, designed for students without a bachelor's degree in computing to participate in computing research. 
* Identify wearable sensors that are the least invasive and provide the most insight into a patient's long-term stress levels to determine effectiveness of counseling/psychotherapy.
* Develop a framework for machine learning techniques to quantify the impact that different sensors (e.g., heart rate, galvanic skin response) have on determining stress levels to help practitioners select the most suitable sensor(s) to recommend to patients undergoing therapy.
* Identify best practices for data collection, cleaning, and processing.
