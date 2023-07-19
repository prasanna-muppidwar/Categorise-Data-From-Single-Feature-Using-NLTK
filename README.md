# Categorise-Data-From-Single-Feature-Using-NLTK

## Description 
1. I preprocessed product names by extracting only nouns using NLTK, then used TF-IDF vectorization to convert them into numerical representations.
2. Used K-Means clustering to group similar product names into 20 clusters.
3. Aggregated product details (main category, subcategory, actual price) for each cluster.
4. Named each cluster based on the most common words in its product names.
5. Created a DataFrame with cluster names, product names, and related details.
6. Saved the results in 'sports.csv'.

## Dataset
[Amazon Product Sales 2023](https://www.kaggle.com/datasets/lokeshparab/amazon-products-dataset)

