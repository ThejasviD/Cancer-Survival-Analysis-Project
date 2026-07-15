In this study, we investigated if G-Cross (the distance between tumor cells and immune cells) is significantly associated with survival for participants with Head and Neck Squamous Cell Carcinoma (HNSCC) and assessed its predictive value after adjusting for known predictors. The data came from two sources, The Cancer Genome Atlas (TCGA), and the University of Michigan (UMich). Missing data was imputed with Multiple Imputation using Chained Equations. Multivariable Cox proportional hazards models were used to model the hazard of death. TCGA data was used as training data for model selection, and reduced models were created with and without G-Cross included. We ran the reduced models on the UMich testing data, and compared C-index and Brier scores to evaluate the prediction value of G-Cross. All analysis was done in R.

The files are as follows:
"699Project2": Data cleaning and exploratory data analysis
"699Project2Imputation": Running Multiple Imputation using Chained Equations
"699Project2Models": Running the multivariable Cox proportional hazards models
"699Project2Testing": Comparing models using C-index and Brier scores
"699Project2Report": Full written report with results
