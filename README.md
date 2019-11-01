# Google-App-Pricing-Analyst
This is a project that analyzes App pricing strategies in order to provide suggestions for App developers. 

The data we used is gathered from Kaggle, comprising name, category, size, version and other detailed information of more than 10000 apps in Google Play Store. Through the feature engineering and model building of our analysis of this dataset, we hope to gain more insights about the price distributions of the apps and make optimal price prediction for newly developed apps, helping the apps reach more potential audiences. 

The dataset includes two CSV files, one is about details of apps with a total of 13 columns and 10841 rows, the other file is about the corresponding comments of the apps given by history users. After researching on the price distribution of apps and what factors may influence the price setting, we will conduct text analysis to further study what makes a popular app in the real-world market according to the customer reviews.

During the project, we firstly pre-processed the data. Cleaning for each column included but were not limited to: checking and processing null value, changing data type, deleting obvious errors, viewing data distribution (histogram), splitting or merging data.

Later in the feature engineering process, we got several thought-provoking findings for the following questions. For example, why most apps are free of charge while downloading? Are they really free? What categories are the paid apps belong to? Are the paid apps rated higher than the free apps by customers? All of these questions come from the vivid graphs we generated. And we gave our plausible explanations in this part.

Finally, we built models to analyze the factors affecting apps pricing and rating. Linear regression, logistic regression, random forest models were built. The simulation accuracy rate is high, which partly attributes to the biased dataset and too much apps are set free. Through investigation, we found that a large number of apps are now profitable by providing other paid services after downloading. So we suggest "free download first, then customized serves are charged later" for most app development in order to gain more customers when new apps firstly release.



