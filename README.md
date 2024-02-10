# Amazon-Electronics-Recommendation
Conducting an exploratory analysis on collaborative filtering recommendation algorithms, this study examines memory-based approaches such as item-based, user-based, and model-based SVD using the Amazon Electronics recommendation dataset.

# Dataset 

## Dataset Description:

The dataset used in this project is an updated version of the Amazon review dataset released in 2014. It encompasses a vast collection of reviews, product metadata, and transaction details spanning from May 1996 to October 2018. With a total of 233.1 million reviews, this dataset offers a comprehensive exploration of user interactions and product attributes across various categories. Notably, it includes detailed metadata such as product descriptions, technical specifications, and images, providing rich insights into user preferences and product features.

## Dataset Source:

The dataset is sourced from the "Small" subsets for experimentation section of the Amazon review dataset. Specifically, I chose the **Electronics (Rating only)** subset, which consists of user-item interactions represented by floating-point ratings ranging from 1 to 5, indicating low to high ratings, respectively.

## Dataset Link:

You can access the [dataset](https://cseweb.ucsd.edu/~jmcauley/datasets/amazon_v2/) here.


# Usage

The provided Colab notebook `amazon_recommender_system.ipynb` can be used seamlessly with the dataset loaded directly from Google Drive. If you're running the notebook on Google Colab, ensure that the dataset is located at the specified path in your Google Drive: `/content/drive/MyDrive/amazon/Electronics.csv`

# Insights
* Achieved a test-set RMSE of 1.3099 with item-item filtering and 1.0754 with user-user filtering using KNN baseline with 5 neighbors
* Achieved a test-set RMSE of 1.2844 with SVD with 10 epochs, 0.005 learning rate and 0.4 regularization, chosen using grid search

  
# Citation

*Justifying recommendations using distantly-labeled reviews and fined-grained aspects*  
*Jianmo Ni, Jiacheng Li, Julian McAuley*  
*Empirical Methods in Natural Language Processing (EMNLP)*, 2019  
[PDF](https://cseweb.ucsd.edu/~jmcauley/pdfs/emnlp19a.pdf)

