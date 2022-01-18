# Data Science Projects Portfolio

## [Project 1: House Price Prediction Project](https://github.com/chelseako/House_Pricing_Project)
* Created a model that estimates sold prices for Honolulu houses (RMSE ~ $87,000) to help home buyers estimate a competitive bid offer.
* Custom built a web scraper using Python and Selenium for a local real estate website.
* Used only predictor variables that can be identified at time of listing.
* Cleaned 700+ observations of Honolulu houses sold within the past year using Python (Pandas, Numpy) and R.
* Optimized Linear, Ridge, Lasso, and Elastic Net Regressors to identify model with best predictive validity.

![Scatterplot of sold versus original price](/Images/scatter_sold_orig.png)

## [Project 2: FIFA 2019 Player Position Classifer](https://github.com/chelseako/FIFA_2019_Project)
* Created a linear discrimnant analysis (LDA) model that predicts player position (forward, midfielder, defender) with a cross-validated accuracy of 81%.
* Model can be used to assist club managers in determining what position best suits a player.
* Used principal component analysis (PCA) and factor analysis to reduce dimensionality and explore variable factoring.
* Identified five factors among numeric variables (overall, defending ability, size and movement, potential, and physical ability).
* As expected, the classifier had greater difficulty distinguishing between the midifielder and forward positions and the midfielder and defender positions, indicating greater overlap between midfielder and the other two positions.
* If club managers needed more forwards or defenders for their teams, they could examine their midfielder players' stats on the five identified factors to identify midfielders that are more likely to be successful as a forward or defender.

![3D Principal Component Analysis plot](/Images/3Dplot.png)
