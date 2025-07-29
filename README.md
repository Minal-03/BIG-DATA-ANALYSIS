# BIG-DATA-ANALYSIS

*COMPANY*: CODTECH IT SOLUTIONS

*NAME*: MEENAL

*INTERN ID*: CT06DF1241

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH
## The objective of this task was to demonstrate the ability to analyze a large-scale dataset using scalable data processing tools like Dask, and to derive meaningful insights from the data. The dataset used contained over 980,000 Amazon Kindle Store reviews spanning from 1996 to 2014, making it ideal for testing scalability and performance under large data volumes.

The analysis began by loading the dataset with Dask, a parallel computing library in Python designed to handle data that does not fit into memory. Dask's lazy evaluation and chunked processing allowed for efficient data handling without overloading the system. The dataset included key attributes such as product ID (asin), star ratings (overall), review text, review helpfulness, timestamps, and user identifiers.

Data cleaning involved parsing the helpfulness column into numerical values, handling missing data, and ensuring consistent data types. Using Dask’s groupby and aggregation functions, several core analyses were performed — such as distribution of ratings, average helpfulness ratio, review length by rating, and identifying top-rated products. All operations were completed efficiently thanks to Dask’s ability to process data in parallel.

The rating distribution revealed that the vast majority of reviews (over 58%) were 5-star, and more than 84% were either 4- or 5-star. This indicated a strong positive bias in the reviews, which may reflect customer satisfaction or selection bias in what users choose to review. Interestingly, only about 2% of the reviews were 1-star, suggesting low dissatisfaction or underreporting of negative experiences.

The helpfulness ratio—defined as the percentage of users who found a review helpful—was consistently around 36–37% across all rating levels. This suggests that review helpfulness is not heavily influenced by whether the review is positive or negative, but likely depends more on clarity, length, or specific content of the review.

The task also uncovered that longer reviews tended to be written for 3-star or lower-rated products, indicating that less satisfied users often provide more detailed feedback. Additionally, a list of top-rated products was identified — those with near-perfect average ratings and at least 50 reviews — helping highlight products that consistently perform well in customer feedback.

Time-based analysis showed a sharp increase in review volume between 2008 and 2014, coinciding with the rising popularity of Amazon Kindle devices and e-books.

In summary, this task successfully demonstrated how big data tools like Dask can be used not only to process datasets that exceed memory limits, but also to generate valuable, interpretable insights. From a technical perspective, it showcased the benefits of scalable computing, while from a business standpoint, it helped understand user satisfaction trends, product performance, and behavior over time. The final deliverable — a well-documented Jupyter Notebook — captured the entire workflow, making the analysis reproducible, insightful, and ready for extension to other domains or datasets
