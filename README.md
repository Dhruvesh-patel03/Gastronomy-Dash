# Gastronomy-Dash

In this project, we explore and analyze restaurant data to uncover valuable insights related to customer preferences and restaurant ratings. We build predictive regression models to estimate aggregate restaurant ratings based on various features, including price range, votes, and the availability of table booking or online delivery. Additionally, we perform data visualizations to illustrate key trends and correlations.

🛠️ Technologies Used
Python
Pandas
Scikit-learn
Matplotlib
Seaborn
Google Colab (for dataset uploading)


📂 Project Structure
├── README.md                # Project overview and documentation
├── Dataset.csv              # Dataset (replace with your actual dataset)
├── restaurant_rating_analysis.py # Python script for data analysis and modeling
└── requirements.txt         # Python libraries required


📊 Analysis and Insights
1️⃣ Customer Preference Analysis
Cuisine Ratings: Analyzed the relationship between cuisines and ratings to uncover which cuisines are most popular and highly-rated.
Cuisine Popularity: Examined the popularity of cuisines based on the total number of votes.
2️⃣ Regression Models for Rating Prediction
We implemented three machine learning regression algorithms to predict a restaurant's aggregate rating:
Linear Regression
Decision Trees
Random Forest
We evaluated model performance using metrics such as:
Mean Absolute Error (MAE)
Mean Squared Error (MSE)
R² Score
3️⃣ Data Visualization
Distribution of Ratings: Explored the distribution of ratings using histograms.
Cuisine-wise Ratings: Visualized the average ratings for the top 10 cuisines.
City-wise Ratings: Compared the average ratings across different cities.
Votes vs Ratings: Investigated the relationship between the number of votes and the aggregate rating.
Price Range and Ratings: Examined how the price range correlates with ratings.
Correlation Heatmap: Displayed correlations between key features like votes, price range, and aggregate rating.


📈 Results
Model	MAE	MSE	R²
Linear Regression	0.45	0.31	0.82
Decision Tree	0.38	0.25	0.85
Random Forest	0.35	0.22	0.87


📜 Conclusion
Random Forest emerged as the best-performing model in terms of R² score and prediction accuracy.
Highly-rated Cuisines: Some cuisines tend to consistently receive higher ratings, offering insights into customer preferences.
The visualizations offer actionable insights that can guide restaurant owners in making data-driven decisions to enhance customer satisfaction.
