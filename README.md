# Social Media Engagement Rate Prediction

## Overview

This machine learning project predicts the **Engagement Rate** of social media posts using various post characteristics and user metrics.

The project includes:

- Data preprocessing
- Feature engineering
- Correlation analysis
- Model comparison
- Feature importance analysis
- Engagement Rate prediction

---

## Dataset Features

### Input Features

- Platform
- Content Type
- Category
- Views
- Likes
- Comments
- Shares
- Saves
- Follower Count
- Hour of Day
- Day of Week
- Hashtag Count
- Content Length
- Sentiment
- Influencer Tier
- Has Media
- Is Verified

### Engineered Feature

- Total Interactions

---

## Target Variable

- Engagement Rate

---

## Models Compared

| Model | R² Score |
|---------|---------|
| Linear Regression | 0.0504 |
| Random Forest Regressor | 0.3113 |
| Extra Trees Regressor | 0.3078 |
| Gradient Boosting Regressor | 0.3772 |

### Best Model

**Gradient Boosting Regressor**

---

## Evaluation Metrics

- R² Score: 0.3772
- MAE: 8.38
- RMSE: 98.59

---

## Correlation Insights

- Views and Saves show moderate positive correlation.
- Follower Count has weak correlation with Engagement Rate.
- Engagement Rate is influenced by multiple factors rather than a single feature.

---

## Top Important Features

1. Follower Count
2. Total Interactions
3. Content Length
4. Hour of Day
5. Views

---

## Technologies Used

- Python
- Pandas
- NumPy
- Scikit-Learn
- Matplotlib
- Jupyter Notebook

---

## Project Structure

```text
data/
    social_media_engagement_dataset.csv

models/
    social_media_model.pkl

sample.ipynb

README.md
```

---

## Future Improvements

- Hyperparameter tuning
- Cross-validation
- XGBoost implementation
- Deep Learning models
- Deployment using Streamlit

---

## Author

Nidsr2823-dev
