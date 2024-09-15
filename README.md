# Book Genre Classification

## Application of Multinomial Naive Bayes for Genre Classification of Books

### Summary
In this project, a genre classification model was built to predict the genre of a book based on its description. The project included data preparation, text feature extraction, model training, and evaluation, as well as visualizations of book ratings.

### Methodology

1. **Data Preparation**:
   - **Missing Values**: Dropped rows with missing descriptions and genres.
   - **Sampling**: Randomly sampled 10% of the dataset for analysis.

2. **Feature Extraction**:
   - **Text Vectorization**: Converted text descriptions into numerical features using `CountVectorizer` with a limit of 500 features.

3. **Model Training and Evaluation**:
   - **Data Splitting**: Divided the dataset into training and testing sets.
   - **Classifier**: Trained a `MultinomialNB` model on the training data.
   - **Prediction and Evaluation**: Evaluated the model's performance using accuracy and classification report metrics.

4. **Visualizations**:
   - **Histogram**: Plotted the distribution of book ratings.
   - **Scatter Plot**: Displayed ratings vs. number of ratings.

### Skills Used
- **Data Handling**: Efficient manipulation and sampling of datasets using Pandas.
- **Feature Extraction and Vectorization**: Transforming text data into numerical features using `CountVectorizer`.
- **Machine Learning Algorithms**: Application of `MultinomialNB` for classification tasks.
- **Model Evaluation Metrics**: Assessment of model performance using accuracy and classification report.
- **Data Visualization**: Creating histograms and scatter plots using Matplotlib.

### Results
The project results include:
- **Model Performance**: Accuracy and classification report metrics.
- **Visualizations**: Distribution of book ratings and scatter plot of ratings vs. number of ratings.
