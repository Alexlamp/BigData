# BigData

Objectives:

In this challenge, I will perform the ETL process completely in the cloud and upload a DataFrame to an RDS instance. I will use PySpark to perform a statistical analysis of the selected data.

Perform ETL on one of the review datasets.
Store your results on an AWS RDS database.
Determine if reviews are biased using PySpark or SQL with the appropriate statistical methods.

Materials:

Amazon Web Services 
Amazon S3 
RDS
Google Colab Notebooks
pgAdmin 4
Visual Studio Code
Data Source: https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Music_v1_00.tsv.gz

Submission:
https://colab.research.google.com/drive/1BfeM_uopelzatpXoAafFZBoaY2r3nQpY?authuser=2#scrollTo=4heimnL40MZT

After splitting the reviews between vine (paid) and non-vine (unpaid), these are my results:

-Music Reviews-

1.  There were 1,962,055 total unpaid reviews.
2.  There were 7 total paid reviews. 
3.  There were 1,475,272 total unpaid helpful 5-star reviews.
4.  There were 3 total paid 5-star helpful reviews.

Conclusion:

There is a very small data set of Vine (paid) reviews compared to the unpaid reviews. In total there are only 7 total paid reviews compared to the 1,962,055 unpaid reviews. The large sample size of unpaid reviews is significant and trustworthy. In contrast, the insignificant sample size of paid reviews makes these reviews untrustworthy. In conclusion, the paid reviews are untrustworthy; however, the sample size is too small to make a significant difference to the overall ratings.  
