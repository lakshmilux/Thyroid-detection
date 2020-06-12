# Thyroid-detection
Problem Statement
To build a classification methodology to predict the type of Thyroid based on the given training data. 
Architecture
  
Data Description
The client will send data in multiple sets of files in batches at a given location. Data will contain different classes of thyroid and 30 columns of different values.
"Class" column will have four unique values “negative, compensated_hypothyroid,
primary_hypothyroid, secondary_hypothyroid”.

Apart from training files, we also require a "schema" file from the client, which contains all the relevant information about the training files such as:
Name of the files, Length of Date value in FileName, Length of Time value in FileName, Number of Columns, Name of the Columns, and their datatype.

Then, different models are trained depending upon the data.The best model is obtained which has the best precision and Recall 
Now,The model is deployed in the Heroku cloud.
