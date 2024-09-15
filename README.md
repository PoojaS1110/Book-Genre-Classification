# Book Genre Classification

## Application of Logistic Regression for Genre Classification of Books

### Summary

In this project, a genre classification model was built to predict the genre of a book based on its title, author, and description. The objective was to classify books into various genres using features from their metadata. The project involved data cleaning, text preprocessing, feature extraction, and model training, culminating in genre prediction and evaluation.

### Methodology

**Data Cleaning and Preprocessing**:
- **Text Cleaning**: Removed non-alphabetical characters, converted text to lowercase, and trimmed extra spaces from titles, authors, and descriptions.
- **Missing Values**: Handled missing values and removed duplicate entries to ensure data quality.

**Feature Extraction**:
- **TF-IDF Vectorization**: Converted the text data (title and description) into numerical features using TF-IDF (Term Frequency-Inverse Document Frequency).

**Model Training and Evaluation**:
- **Data Splitting**: Divided the dataset into training and testing sets.
- **Classifier**: Trained a Logistic Regression model on the training data.
- **Prediction and Evaluation**: Evaluated the model's performance using metrics such as accuracy, precision, recall, and F1-score.

### Skills Used

- **Data Cleaning and Preprocessing**: Techniques for preparing text data for analysis.
- **Feature Extraction and Vectorization**: Methods for transforming text data into numerical features using TF-IDF.
- **Machine Learning Algorithms**: Application of Logistic Regression for classification tasks.
- **Model Evaluation Metrics**: Utilized accuracy, precision, recall, and F1-score to assess model performance.
- **Data Handling with Pandas**: Efficient manipulation and analysis of dataset.

### Results

The project resulted in a CSV file named `test_with_predictions.csv`, which includes:
- **Original Book Data**: Titles, authors, and descriptions of books from the dataset.
- **Predicted Genre Classifications**: The genre predicted by the model based on the book's title and description.

The results demonstrated the effectiveness of text preprocessing and classification techniques in predicting book genres and provided practical insights into the application of machine learning algorithms for text-based classification tasks.

