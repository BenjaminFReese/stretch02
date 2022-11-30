# stretch02
The code in strech02.qmd creates stretch02.html. The analysis contained within stretch02 predicts why civil servants leave federal service. More specifically, the model tries to classify civil servants' exit decisions based on if they quit or if they left for some other reason. The code begins by loading in three distinct datasets. A dataset from the Office of Personnel Management that has civil servant exit data, a dataset with economic variables from Michael Bailey's Real Stats, and presidential approval rating data. More information about these datasets can be found in stretch02.html. Once the data is loaded, I clean each dataset, create a categorical civil servant education variable, create the "quit" or "not quit" variable, and then join the three datasets together by quarter. Due to the different cross-sections included in the three different datasets, I end only with the years of 2005-2009. 
Once the data is cleaned, I conduct some basic exploratory data analysis shown in a series of data visualizations. After the EDA, I split the data into a training and testing set, describe and specify a logistic regression, random forest, and CART machine learning models, and implement the CART model. Stretch02.html ends with my presentation of the best model results and a discussion of the error metric. Overall, accuracy is about .68 and recall about .53. While the recall is not great, and recall is one of the most important error metrics for this model, the accuracy is not terrible. Regardless of the accuracy, the results indicate that employees are more likely to quit in the early days of their service compared to longer serving employees. The final discussion in the paper is about next steps and includes arguments for improved feature selection and modeling decisions.
