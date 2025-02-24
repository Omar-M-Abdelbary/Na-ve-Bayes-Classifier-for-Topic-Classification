# Na-ve-Bayes-Classifier-for-Topic-Classification

## Overview
This project implements a topic classification model using the Naïve Bayes classifier. The classifier is trained on text documents retrieved from Wikipedia and is capable of predicting the domain of unseen text data.

## Features
- Downloads Wikipedia articles from two different domains for training and testing.
- Preprocesses the text data (tokenization, cleaning, and feature extraction).
- Implements a Naïve Bayes classifier from scratch.
- Evaluates the classifier's performance.

## Dataset
The dataset consists of Wikipedia articles automatically fetched using the Wikipedia API. The articles belong to two different domains, ensuring diverse topic representation.

## Installation
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/your-repository.git
   cd your-repository
   ```
2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```
   Ensure you have the necessary libraries such as `wikipedia-api`, `numpy`, and `scikit-learn` installed.

## Usage
Run the Jupyter Notebook to execute the project step by step:
1. Open Jupyter Notebook:
   ```bash
   jupyter notebook
   ```
2. Load and run the notebook `the-Naive-Bayes-classifier.ipynb`.

## Project Structure
- `the-Naive-Bayes-classifier.ipynb`: Jupyter Notebook containing code and explanations.
- `requirements.txt`: List of dependencies.

## Results
The classifier is trained and evaluated on Wikipedia text data, providing accuracy metrics for classification performance.

## Contributing
Feel free to fork this repository and submit pull requests for improvements.

## License
This project is open-source and available under the MIT License.

