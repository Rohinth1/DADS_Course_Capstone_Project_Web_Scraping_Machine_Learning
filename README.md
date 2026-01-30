**PROJECT TITLE**  

E-Commerce Product Analysis Using Machine Learning  

**INTRODUCTION**  

This project applies data science and machine learning techniques to analyze product data collected from an e-commerce website. The primary goal was to identify patterns in pricing and ratings and evaluate how well these features could predict product categories. Both unsupervised and supervised learning methods were used to extract insights from the dataset.  

**DATA COLLECTION**  

The dataset was obtained through web scraping using Python libraries. Key attributes collected included product name, price, category, and rating. The data was stored in CSV format to enable further processing and analysis. This step ensured that sufficient data was available for modeling and evaluation.  

**DATA CLEANING** 

Data cleaning involved standardizing price formats, converting ratings into consistent values, and removing missing or duplicate records. Proper formatting and type conversion ensured the dataset was suitable for analysis. These steps improved data reliability and minimized potential errors in modeling.  

**EXPLORATORY DATA ANALYSIS**  

Exploratory analysis was conducted to understand the distribution of price and rating variables. Visualizations revealed that prices were fairly spread across a range, while ratings showed balanced representation across categories. Insights suggested that price and rating alone may not strongly determine product categories.  

**FEATURE SCALING**  

Feature scaling was applied using standardization to normalize numerical values. This step was necessary for algorithms sensitive to feature magnitude, such as K-Means, Logistic Regression, SVM, and KNN. Scaling ensured fair contribution of each feature during model training.  

**UNSUPERVISED LEARNING**  

K-Means clustering was used to identify natural groupings based on price and rating. The elbow method and silhouette score helped determine the optimal number of clusters. Results showed that products grouped primarily by pricing patterns, indicating meaningful segmentation within the data.  

**SUPERVISED LEARNING** 

Several classification models were implemented, including Logistic Regression, Support Vector Machine, K-Nearest Neighbors, Random Forest, and XGBoost. These models aimed to predict product categories using price and rating features. Performance metrics such as accuracy and F1-score indicated modest predictive capability, highlighting limited feature influence.  

**MODEL EVALUATION**  

Model comparison revealed that simpler models performed similarly to more complex ensemble methods. Hyperparameter tuning resulted in minor improvements but did not significantly enhance predictive power. This reinforced that feature informativeness plays a critical role in classification tasks.  

**CONCLUSION**  

The project demonstrated a complete machine learning workflow from data collection to model evaluation. Unsupervised learning revealed meaningful data patterns, while supervised models showed limited success in category prediction. The findings emphasize the importance of richer feature sets for improving model performance and provide a foundation for future enhancements.
