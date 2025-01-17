# N-gram Language Model for Sentiment Analysis

This repository contains a Jupyter Notebook that demonstrates the implementation of an n-gram language model for sentiment analysis using the IMDB Dataset.

## Overview

The notebook explores the following aspects of n-gram language modeling:

- **Data Preprocessing:** Cleaning and preparing the IMDB dataset for analysis.
- **N-gram Generation:** Creating unigrams, bigrams, trigrams, quadgrams, and pentagrams from the text data.
- **Probability Calculation:** Computing n-gram probabilities using various smoothing techniques:
    - Laplace Smoothing
    - Good-Turing Discounting
    - Kneser-Ney Smoothing
- **Model Evaluation:** Assessing the performance of the language model using perplexity as a metric.
- **Cross-Validation:** Employing cross-validation to ensure model robustness.
- **Visualization:** Presenting the results with clear and informative plots.

## Requirements

To run this notebook, you'll need the following:

- Python 3.x
- Jupyter Notebook or Google Colab
- NLTK library
- Pandas library
- NumPy library
- Matplotlib library
- Scikit-learn library

## Installation

1. Install the required libraries using `pip`: `install` `nltk` `pandas` `numpy` `matplotlib` `scikit-learn`

2. Download the necessary NLTK resources: `import nltk nltk.download('movie_reviews') nltk.download('punkt')`

## Usage

1. Open the `n-gram.ipynb` notebook in Jupyter Notebook or Google Colab.
2. Execute the code cells sequentially to perform the analysis.
3. Modify the parameters and experiment with different n-gram sizes and smoothing techniques.

## Dataset

The IMDB Dataset is used for this analysis. It consists of movie reviews labeled as positive or negative. You can download the dataset from [this link]. Make sure to update the file path in the notebook to reflect the location of the dataset on your system.


## Results

The notebook includes visualizations and analysis of the model's performance, including perplexity scores and comparisons between different smoothing techniques.


## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvement, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License.