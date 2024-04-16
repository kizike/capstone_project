# Applied Data Science capstone project
Coursera - IBM Data Science course - Applied Data Science capstone project
# Description
SpaceX stands out in the aerospace industry thanks to its revolutionary idea of making the first stage of the rocket reusable. SpaceX offers Falcon 9 rocket launches at a cost of $62 million, while other providers charge upwards of $165 million per launch. Most of the savings come from recovering the first stage of the launch by re-landing the rocket for use on the next mission.
The goal of this project is to create a machine learning pipeline to predict the landing outcome of the first stage in the future. Having this information can help a competitor company to bid against SpaceX for a rocket launch.
Solving this problem involves:
- Collecting information on historical SpaceX launches
- Determining the key factors that contribute to the success of a landing
- Finding the best performing machine learning algorithm for prediction

# Executive Summary
The following methodologies were used for this project:

Data collection methodology:
- Data was collected using SpaceX REST API and web scraping from Wikipedia
Perform data wrangling
- Data was cleaned and then processed using one-hot encoding for categorical features
Perform exploratory data analysis (EDA) using visualization and SQL
Perform interactive visual analytics using Folium and Plotly Dash
Perform predictive analysis using classification models
- Build models to predict landing outcomes using Logistic regression, Support Vector Machine (SVM), Decision Tree and K-nearest Neighbor (KNN)

# Results

**Model performance**: The models performed similarly on the test set. Due to the risk of overfitting on a small dataset, it advisable to avoid selecting more complex models. A less computationally intensive model is also a good choice (reduced training and prediction time). 
**Launch site**: All of the launch sites are near the equator and near coastlines.
**Launch success:** The launch success rate increases with time.
**Launch sites success rate:** KSC LC-39A site has the highest success rate amongst all sites.
**Payload Mass:** The higher the payload mass (kg), the higher the success rate.
**Dataset size:** The dataset was relatively small. It is worth considering collecting more data to improve the model performance, prediction accuracy and reduce the false positive rate. 

