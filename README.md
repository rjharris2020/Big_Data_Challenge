# "Alexa, can you handle big data?"

## Instructions

### Level 1
Use the furnished schema to create tables in your RDS database.

Create two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook.

For each notebook (one dataset per notebook), complete the following:

Count the number of records (rows) in the dataset.

Transform the dataset to fit the tables in the schema file. Be sure the DataFrames match in data type and in column name.

Load the DataFrames that correspond to tables into an RDS instance. Note: This process can take up to 10 minutes for each. Be sure that everything is correct before uploading.

### Level 2 (optional)
In Amazon's Vine program, reviewers receive free products in exchange for reviews.

Amazon has several policies to reduce the bias of its Vine reviews: https://www.amazon.com/gp/vine/help?ie=UTF8.
But are Vine reviews truly trustworthy? Your task is to investigate whether Vine reviews are free of bias. Use either PySpark or—for an extra challenge—SQL to analyze the data.

If you choose to use SQL, first use Spark on Colab to extract and transform the data and load it into a SQL table on your RDS account. Perform your analysis with SQL queries on RDS.

While there are no hard requirements for the analysis, consider steps you can take to reduce noisy data, e.g., filtering for reviews that meet a certain number of helpful votes, total votes, or both.

Submit a summary of your findings and analysis.
