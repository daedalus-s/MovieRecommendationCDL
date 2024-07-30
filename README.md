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
