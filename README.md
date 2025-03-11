# Advanced Recommender System Project
## Project Overview
This project involves designing, implementing, and evaluating a recommendation system that leverages multiple data sources to predict user preferences. The goal is to maximize prediction accuracy across four test scenarios, covering both common and challenging real-world recommendation tasks.

## The project involves:

Predicting user ratings for items using warm-start and cold-start test cases.
Identifying user preferences between pairs of items in pairwise comparison tasks.
Integrating multiple data sources, including user interactions, item metadata, and images.
This project allows experimentation with collaborative filtering, content-based filtering, and hybrid deep learning models to build a robust recommendation system.

## Project Objectives
The recommendation system will be evaluated based on four key tasks:

### Rating Prediction Tasks:

Warm Items: Predict user-item ratings for items present in the training dataset.
Cold Items: Predict user-item ratings for items with no prior interactions but available metadata and images.
### Pairwise Comparison Tasks:

Warm Items: Predict user preferences between pairs of items with historical interactions.
Cold Items: Predict user preferences between pairs of items with no prior interactions but rich contextual information.
## Data Integration:

Utilize user interactions, item metadata, and images to improve recommendation accuracy.
Project Dataset
### The dataset consists of three components:

 - User-Item-Rating File (CSV)
Contains user_id, parent_asin (item ID), rating, and timestamp.
Includes approx. 1,000,000 users, 220,000 items, and 10,000,000 ratings.

 - Metadata File (JSONL)
Contains detailed item information, including categories, descriptions, images, prices, features, and related items.

 - Images Folder
Contains high-quality product images for each item, identified by their parent_asin.

## Test Set
The evaluation includes four test scenarios:

### Warm-Items Rating Prediction
Predict ratings for items already present in the training data.

### Cold-Items Rating Prediction
Predict ratings for new items not seen in the training data.

### Warm-Items Pairwise Comparison
Predict user preference between pairs of items with historical interactions.

### Cold-Items Pairwise Comparison
Predict user preference between pairs of new items based on metadata and images.

### Deliverables
Predicted Ratings: Submit CSV files with predicted ratings for user-item pairs.
Pairwise Predictions: Submit CSV files with predicted preference classes (0 or 1).

### Dataset availability
https://amazon-reviews-2023.github.io/

