# Sentiment Analysis
Sentiment analysis is the interpretation and classification of emotions (positive, negative and neutral) within text data using text analysis techniques. Sentiment analysis tools allow businesses to identify customer sentiment toward products, brands or services in online feedback.



# Intro
All the data is from the Kaggle platform, provided by Shopee.
## Background
At Shopee, we always strive to ensure the customer’s highest satisfaction. Whatever product is sold on Shopee, we ensure the best user experience starting from product searching to product delivery, including product packaging, and product quality. Once a product is delivered, we always encourage our customer to rate the product and write their overall experience on the product landing page.

The rating and comments provided for a product by our buyers are most important to us. These product reviews help us to understand our customers needs and quickly adapt our services to provide a much better experience for our customers for the next order. The user's comments for a product ranges from aspects including delivery services, product packaging, product quality, product specifications, payment method, etc. Therefore it is important for us to build an accurate system to understand these reviews which has a great impact on overall Shopee’s user experience.
## Datasets
There are ~150k product reviews from different categories, including electronics, furniture, home & living products like air-conditioner and fashion products like T-shirts, rings, etc. 

### File description
- train.csv - the training set
- test.csv - the test set
- sampleSubmission.csv - a sample submission file in the correct format
### Data fields
- review_id - an anonymous id unique to a given user comments
- review - User comments in english
- rating - The actual user rating for that comments.
### Train.csv
| review_id | review  | rating  |
| :---:   | :-- | :-: |
|11576 | It's working properly. Very <br> quick heating capability.<br> Good product with this <br>price thanks | 5 |
|10293 | Excellent service by the <br> staff, helpful and polite.<br> Great experience overall. | 5 |
|01820 | The delivery was fast but <br>the packaging was not <br>that good, the price is <br>reasonable, overall the <br>product is ok., | 4 |
|32090 | Package not that well | 2 |
|..... | ..... | .....|
