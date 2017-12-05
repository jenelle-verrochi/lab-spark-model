# Apache Spark: Model building

Now that we've had some practice building models in Apache Spark, it's time to put your skills to the test!

Using the `Credit.csv` dataset from [ISLR](http://www-bcf.usc.edu/~gareth/ISL/data.html), you will build a regression model to predict the credit balance (`Balance`) given the following features:

- Income
- Limit
- Rating
- Cards
- Age
- Education
- Gender*
- Student*
- Married*
- Ethnicity**

*Needs to be indexed with `StringIndexer`

**Needs to be indexed with `StringIndexer` and one-hot encoded with `OneHotEncoder`


## Train/Test split
1. Split the data into an 80/20 train/test split. Use **2** for your random seed so we can have consistent scores across the board.
2. Paste your best R2 score from the test set below (My best was 0.9359)

R2 Score: 0.9477

## Publish your notebook
You're going to publish your notebook rather than submitting it in this rep. In DataBricks, select File > Publish and paste your URL below:

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/5077982375206005/2286219156696855/6486725442478487/latest.html
