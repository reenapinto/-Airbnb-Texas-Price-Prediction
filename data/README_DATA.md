Large parquet files (cleaned_reviews1.parquet, cleaned_reviews2.parquet) 
are hosted on Kaggle due to GitHub file size limits.

Dataset link:
https://www.kaggle.com/code/reenamaritapinto/airbnb-texas-price-prediction

Although reviews data was cleaned and explored, it was not used directly in the pricing model. 
Instead, aggregated demand signals (reviews_per_month, number_of_reviews_ltm) were used from 
the listings table to avoid data leakage and reduce dimensionality.
