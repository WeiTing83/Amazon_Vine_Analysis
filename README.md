# Amazon_Vine_Analysis
### Overview of the analysis: 
We analyze Amazon Toy review. The data is collected from
Amazon Vine program which is a service that the company
provides products to Vine members who are required to publish
reviews. Additionally, the data include the preview from non-Vine
members. We will use PySpark to perform ETL, connect to an
AWS RDS instance and load the transformed data into pgAdmin.
Then, utilizing PySpark to analyze the review for Vine and non-
Vine members.
>
### Results: 
#### Load the transformed data into pgAdmin:
![vine](https://github.com/WeiTing83/Amazon_Vine_Analysis/blob/main/images/vine.png)
![product](https://github.com/WeiTing83/Amazon_Vine_Analysis/blob/main/images/product.png)
>
#### Analysis vine review:
- Vine reviews are 1266 data. ; Non-Vine reviews are 62028
data.
- Vine reviews received 5 stars which are 432 data.
- Non-Vine reviews received 5 stars which are 29982 data.
- Vine reviews and 5 stars are 34.1%
- Non-Vine reviews but 5 stars are 48.3%
>
### Summary:
Based on calculating all toys review, 5 stars for
non-vine and vine reviews show a little
different result in percentage. However, we
need to review products which have lower than
2 stars of evaluation and further evaluate
results in percentage. The product reviews
from Vine members could be more reliable
since they paid for their membership.
Therefore, we can provide products to Vine
members to let the company understand their
products more.
