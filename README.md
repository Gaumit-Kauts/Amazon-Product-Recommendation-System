# Amazon-Product-Recommendation-System

Welcome to the Amazon Product Recommendation System project! In this project, I developed and evaluated multiple recommendation algorithms on a dataset of Amazon product reviews, with a focus on delivering personalized product suggestions. The dataset contains user ratings for various electronic products, and my goal was to build a robust recommendation engine that enhances the user experience and drives higher customer engagement.

## 🚀 Algorithms Implemented:

I explored the following recommendation techniques:

* Rank-based Filtering (using averages) - Simple yet effective ranking based on average ratings.
* User-User Collaborative Filtering - Finds similarities between users to recommend products.
* Item-Item Collaborative Filtering - Recommends products based on item similarity.
* Model-based Collaborative Filtering (Matrix Factorization) - Uses latent factors to predict user preferences.
## 📊 Evaluation & Optimization:

* I used precision@k, recall@k, and F1-score metrics to evaluate model performance. Additionally, grid search cross-validation was applied to tune hyperparameters, optimizing model accuracy and ensuring the best results.

## 🤖 Why Matrix Factorization Stands Out:

After testing various models, the optimized Matrix Factorization approach emerged as the most suitable for this dataset. Key reasons:

* Latent Factor Analysis: Uncovers hidden patterns in user preferences.
* Scalability: Handles large datasets efficiently.
* Robustness to Sparsity: Performs well even with sparse user-item interactions.
* Superior Performance: Achieved the lowest RMSE (0.8814) and highest F1-score (0.863) among all models.

## 🔑 Key Insights:

* Improved Personalization: By leveraging collaborative filtering, I provided highly personalized recommendations.
* Optimization of Business Outcomes: Insights from the model can drive personalized marketing, optimize inventory management, and increase customer satisfaction.

## 💻 Tech Stack:

* Python
* Surprise Library for collaborative filtering
* Grid Search CV for hyperparameter tuning
* Matplotlib and Seaborn for data visualization id
