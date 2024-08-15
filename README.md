# E-commerce Product Recommendation System
This project implements three recommendation system approaches to personalize product suggestions for an e-commerce platform. By leveraging user purchase history, product ratings, and item popularity, the system aims to  enhance customer experience and drive sales.

## Key Approaches

**Recommendation System Part I**: Popularity-Based (For New Customers)

Identifies most popular products based on sales data.
Targets new customers with limited purchase history.

**Recommendation System Part II**: Model-Based Collaborative Filtering

Analyzes user purchase history and item ratings to identify similar user behavior.
Recommends products based on past purchases and preferences of similar users.
Leverages techniques like Singular Value Decomposition (SVD) or Correlation analysis.

**Recommendation System Part III**: Recommendation for New Businesses

Addresses the scenario where a new e-commerce website lacks product ratings.
Employs techniques like k-Means Clustering to group similar products based on item descriptions.
Recommends products within the same cluster as the customer's initial selection.

## Data
The project utilizes datasets from:

Amazon product ratings by multipe users, Data Source: https://www.kaggle.com/skillsmuggler/amazon-ratings

Home Depot products with descriptions, Data Source: https://www.kaggle.com/c/home-depot-product-search-relevance/data


## Usage
Clone the repository.
Install required dependencies (e.g., pandas, numpy, scikit-learn).
Prepare the data (cleaning, preprocessing) according to your specific datasets.
Run the desired recommendation system script.

## Evaluation
The system's effectiveness is evaluated using metrics like precision, recall, F1-score, and RMSE.
