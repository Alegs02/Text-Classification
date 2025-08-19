# Text-Classification
This project involves designing and evaluating text analysis methods using academic article data from arXiv.org. The task is split into two major components:

Part 1: Text Classification
The goal is to build machine learning models to classify whether an article belongs to the Computational Linguistics category based on its title or abstract. The classification task is binary (Computational Linguistics vs. other classes).

You will experiment with multiple configurations by varying:

Input type: Titles vs. Abstracts.

Algorithms: At least one recurrent neural network (RNN) and one statistical classifier (e.g., logistic regression or SVM).

Training size: First 1,000 records vs. the full training dataset.

Pre-processing: A consistent pipeline (e.g., lemmatization, stemming, or stopword removal).

The models will be evaluated using accuracy, precision, recall, F1-score, and precision-recall curves, with analysis focusing on how performance varies across configurations and input types.

Part 2: Topic Modelling
The second component shifts to knowledge discovery using Latent Dirichlet Allocation (LDA) with the training dataset. Two different LDA configurations must be designed and compared, varying factors such as:

Pre-processing strategies.

Use of bigrams.

Number of topics (e.g., K = 10 vs. K = 40).

Both configurations are applied to subsets of 1,000 and 20,000 articles. Visualizations are required to present the extracted topics and illustrate interpretability. The discussion will cover:

The kinds of thematic groupings identified.

Advantages and limitations of topic modelling for uncovering knowledge from research articles.

Comparisons across configurations and dataset sizes.


