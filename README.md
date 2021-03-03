# Movies_Classification_Spark_Databricks
Movies_Classification_Spark_Databricks-PySpark

Project Link (Spark Databricks) : 
https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/7441972598489843/420537623655551/8382657582413507/latest.html

---------------------------------

We are going to build a model making it possible to find the genre of a film (drama, action, thriller, science fiction...) according to its summary. 

Steps :
1. Import the file containing the films into Databricks

2. Partition data into test data and evaluation data

3. Build a pipeline to transform the summary of a film into a TF-IDF vector, apply a classification algorithm (Logistic Regression, Random Forest...)

4. Use a paramGrid and cross validation to optimize the parameters of your model

5. Test the model on the test data.
