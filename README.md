
# Data Science NLP Pipelines

A data science project that uses Natural Language Processing (NLP) techniques to analyze customer reviews and predict whether a user will recommend a product or not. The pipeline includes preprocessing, feature extraction using NLP methods, and classification modeling using logistic regression.

## Getting Started

### Prerequisites

Python 3.10+

Jupyter Notebook

### Dependencies

```
Install the following Python packages:
pandas
numpy
matplotlib
seaborn
scikit-learn
spacy

```

### Installation

Installing using pip
pip install pandas numpy matplotlib seaborn scikit-learn spacy

Installing spacy with:
! python -m spacy download en_core_web_sm

## Testing

The notebook includes basic exploratory and predictive tasks that serve as informal tests of each pipeline component. To run these:

```
Open the notebook in Jupyter Lab or Jupyter Notebook.
Run each cell in sequence to preprocess the data, extract features, train the model, and evaluate performance.
```

### Break Down Tests

```
Text preprocessing test: Verifies tokenization, lemmatization, and stopword removal using spaCy.

Vectorization test: Validates conversion of processed text into TF-IDF vectors.

Model training and evaluation: Logistic regression model is trained, and accuracy is calculated to test predictive performance.
```

## Project Instructions

This project includes the following steps:
```
    Load and explore the dataset of customer reviews.

    Clean and preprocess the text data using spaCy.

    Vectorize the text using TF-IDF.

    Split the dataset into training and test sets.

    Train a logistic regression model.

    Evaluate the model's performance using classification metrics.
```
All student deliverables are presented within the Jupyter notebook, including code, visualizations, and explanations.

## Built With

spaCy - Industrial-strength NLP in Python

scikit-learn - Machine Learning library

pandas - Data manipulation

Jupyter Notebook - Interactive development environment

## License

[License](LICENSE.txt)
