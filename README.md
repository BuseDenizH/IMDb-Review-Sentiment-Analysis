# IMDb Sentiment Analysis
Data Mining term project.

This project uses the [IMDb Movie Reviews Dataset](https://ai.stanford.edu/~amaas/data/sentiment/), which is included in the repository under the `aclImdb` folder.
<hr>
This project implements a sentiment analysis model to classify IMDb movie reviews as positive or negative. The analysis is performed using a <b>manually implemented</b> Logistic Regression model, and <b>no pre-built machine learning libraries</b> are used for training.
<br><br>

Key Features Include:
- Importing Basic Libraries: Loading necessary libraries for the project.
- Loading the Dataset: Selection, loading, and inspection of the IMDb dataset (e.g., number of reviews, types, average lengths).
- Data Preprocessing:
    - Text cleaning: Lowercasing, punctuation removal, stopword removal.
    - Stemming/Lemmatization and calculating average word length.
- Feature Extraction: Manual implementation of Bag of Words (BoW), vocabulary creation, and frequency vectorization.
- Analysis:
    - Sentiment distribution (positive vs. negative review counts).
    - Word count analysis (max-min length, histogram visualization).
    - Most common words (top 10 words in positive and negative reviews).
- Correlation Analysis:
    - Calculating pairwise correlation between features.
    - Visualizing correlations using a correlation matrix.
- Data Splitting: Dividing the dataset into training and testing sets.
- Train Classifier:
    - Logistic Regression implementation with sigmoid function.
    - Manual gradient descent for training with binary cross-entropy loss.
    - Trained over 10 epochs for demonstration (configurable).
- Outlier Detection:
    - Identifying reviews with word counts outside 3 standard deviations from the mean.
    - Visualized using a box plot.
- Association Pattern Analysis:
    - Co-occurrence matrix creation.
    - Visualized using a heatmap.
- Clustering (Optional):
    - Pairwise similarity calculation.
    - Agglomerative Hierarchical Clustering for grouping reviews.
- Evaluate the Model:
    - Logistic Regression predictions with metrics: Accuracy, Precision, Recall, F1-Score.
- Parameter Tuning:
    - Experiments with different learning rates and epoch values to optimize performance metrics.
- Visualization:
    - Bar charts for accuracy and scores across parameters.
    - Confusion matrix visualization for classification results.
- Comparison with Naive Bayes:
    - Naive Bayes classifier for benchmarking performance against Logistic Regression.

<hr>

## How to Run
1. Clone the repository and ensure the IMDb dataset is in the correct directory structure.
2. Open and execute the `.ipynb` file step-by-step in Jupyter Notebook or a compatible environment.
