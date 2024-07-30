# Collaborative Deep Learning for Recommender Systems

This project implements a Collaborative Deep Learning (CDL) model for movie recommendations, combining deep learning techniques with collaborative filtering to overcome limitations of traditional recommender systems.

## Project Overview

Our implementation explores the use of CDL to improve recommendation accuracy, especially in scenarios with sparse data. The model integrates Stacked Denoising Autoencoders (SDAE) with matrix factorization to learn both content-based and collaborative features.

## Dataset

We used the MovieLens dataset, which includes:
- Over 1 million movie ratings
- 6,000+ users
- 3,000+ movies
- Metadata for each movie (title, genre, plot)

## Key Features

- Implements a hierarchical Bayesian model (CDL)
- Combines deep learning with collaborative filtering
- Addresses cold start and data sparsity problems
- Utilizes both implicit feedback and content information

## Project Structure

The project is organized into Jupyter Notebook (.ipynb) files:

1. `data_preprocessing.ipynb`: Data cleaning and preparation
2. `cdl_model.ipynb`: Implementation of the CDL model
3. `evaluation.ipynb`: Model evaluation and results analysis

## Setup and Installation

1. Clone this repository
2. Install required dependencies.
pip install requirements

3. Download the MovieLens dataset and place it in the `data/` directory

## Usage

Open and run the Jupyter Notebooks in the following order:

1. `data_preprocessing.ipynb`
2. `cdl_model.ipynb`
3. `evaluation.ipynb`

## Results

Our implementation achieved a recall of 0.33 for top 300 recommendations.

## Future Work

- Explore more diverse data sources
- Implement advanced deep learning architectures
- Replace bag-of-words with more sophisticated text representation techniques

## References

1. Wang, H., Wang, N., & Yeung, D. Y. (2015). Collaborative deep learning for recommender systems.
2. Wang, C., & Blei, D. M. (2011). Collaborative topic modeling for recommending scientific articles.
3. Hu, Y., Koren, Y., & Volinsky, C. (2008). Collaborative filtering for implicit feedback datasets.
4. Vincent, P., et al. (2010). Stacked denoising autoencoders: Learning useful representations in a deep network with a local denoising criterion.
