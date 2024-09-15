# Book Rating Prediction

## Application of Linear Regression for Predicting Book Ratings

### Summary

In this project, a model was developed to predict the average rating of a book based on its description. The project includes data preparation, text feature extraction, model training using linear regression, and evaluation of the model's performance.

### Methodology

#### Data Preparation
- **Missing Values**: Dropped rows with missing descriptions or ratings.
- **Sampling**: Used the complete dataset for analysis without additional sampling.

#### Feature Extraction
- **Text Vectorization**: Converted book descriptions into numerical features using `CountVectorizer` with a limit of 1000 features.

#### Model Training and Evaluation
- **Data Splitting**: Divided the dataset into training and testing sets (30% for testing).
- **Model**: Trained a `LinearRegression` model on the training data.
- **Prediction and Evaluation**: Evaluated the model's performance using Mean Squared Error (MSE) and R^2 Score.

### Skills Used
- **Data Handling**: Efficient manipulation of datasets using Pandas.
- **Feature Extraction and Vectorization**: Transforming text data into numerical features using `CountVectorizer`.
- **Machine Learning Algorithms**: Application of `LinearRegression` for regression tasks.
- **Model Evaluation Metrics**: Assessment of model performance using MSE and R^2 Score.

### Results

The project results include:
- **Model Performance**: Evaluation metrics such as Mean Squared Error and R^2 Score, which measure the accuracy of the rating predictions.

