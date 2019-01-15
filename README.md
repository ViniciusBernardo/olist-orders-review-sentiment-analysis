# Olist orders review sentiment analysis

This project uses machine learning to make sentiment analysis of Olist orders reviews classifying the score given by the user based on it's message. Olist is a sales engine on the internet where you can anunciate products to sell.

The database was found at the Kaggle platform and is available in [this link](https://www.kaggle.com/olistbr/brazilian-ecommerce#olist_order_reviews_dataset.csv)

The dataset has 100000 rows and 7 columns. Here is a description of the columns:

* **review_id**: unique review identifier
* **order_id**: unique order identifier
* **review_score**: Note ranging from 1 to 5 given by the customer on a satisfaction survey.
* **review_comment_title**: Comment title from the review left by the customer, in Portuguese.
* **review_comment_message**: Comment message from the review left by the customer, in Portuguese.
* **review_creation_date**: Shows the date in which the satisfaction survey was sent to the customer.
* **review_answer_timestamp**: Shows satisfaction survey answer timestamp.