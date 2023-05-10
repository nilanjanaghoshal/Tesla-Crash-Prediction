# Tesla-Crash-Prediction
This analysis aims to predict the number of deaths in Tesla car crashes based on various features like car model, country, autopilot feature, and others.

Data Preprocessing

The first part of the script deals with data preprocessing steps like loading the CSV file into a Pandas DataFrame, dropping unnecessary columns, converting the date column to datetime format, and creating a new column with the month of the crash. The NaN values in the DataFrame are replaced with "not defined" to make the data more usable. The crashes per month are then visualized using a line plot and crashes per year are visualized using a histogram.

The next step involves visualizing the countries that had the highest number of deaths using a bar plot. Another bar plot is used to visualize the number of deaths based on the car model. Finally, a histogram is used to visualize the number of verified Tesla Autopilot deaths.

Feature Engineering and Selection

After the data preprocessing steps, the script performs feature engineering by converting categorical variables to numerical using the Pandas astype() function. The script then splits the data into training and testing sets for model training and evaluation.

Model Training and Evaluation

The script uses three classification algorithms, namely Decision Tree, Random Forest, and Logistic Regression, to predict the number of deaths in Tesla car crashes. The Decision Tree and Random Forest classifiers are first trained and evaluated, and their feature importances are visualized using bar plots. The Logistic Regression model is then trained and evaluated, and its accuracy score is printed.

The confusion matrix of the Decision Tree and Random Forest classifiers are also visualized using heatmaps to evaluate the performance of the models.

Findings

Based on the analysis, the following findings can be made:

1) The number of Tesla car crashes per month and per year has been increasing steadily since 2012, indicating a need for increased safety measures.

2) The Japan and France have the highest number of Tesla car crash deaths, followed by Germany, China and USA.

3) The Model 3 has had the highest number of crash deaths, followed by Model S and Model X.

4) Most of the verified Tesla Autopilot deaths have occurred in the United States.

5) The Decision Tree and Random Forest classifiers both have an accuracy score of over 90%, indicating that they are effective in predicting the number of deaths in Tesla car crashes.

6) The Logistic Regression model has a lower accuracy score of around 70%, indicating that it may not be as effective as the Decision Tree and Random Forest classifiers.

Conclusion

In conclusion, this analysis has highlighted the need for increased safety measures in Tesla cars and the importance of features like car model and country in predicting the number of deaths in Tesla car crashes. The Decision Tree and Random Forest classifiers are both effective in predicting the number of deaths in Tesla car crashes and can be used to inform safety measures in the future. However, more research is needed to improve the accuracy of the Logistic Regression model.
