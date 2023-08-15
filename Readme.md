# Movie Recommendation System using NLP and IMDb Web Scraping

This project implements a sophisticated Movie Recommendation System using Natural Language Processing (NLP) techniques and IMDb web scraping. The system utilizes BERT (Bidirectional Encoder Representations from Transformers) embeddings and IMDb data to provide personalized movie recommendations based on user preferences.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Usage](#usage)
- [Examples](#examples)
- [Author](#author)
- [Acknowledgements](#acknowledgements)
- [License](#license)

## Introduction

Movie recommendation systems have gained immense popularity in recent years for providing tailored content to users.
This project leverages web scraping techniques to extract movie data from IMDb, including titles, descriptions, genres, and 
IMDb ratings. It then utilizes BERT embeddings for text data and cosine similarity to recommend movies that closely match user 
preferences.It is a prompt based system wherein the output will dependt on the quality of the prompt.

## Features

- Scrapes movie data from IMDb, providing comprehensive information including titles, descriptions, genres, and IMDb ratings.
- Extracts details about directors and actors associated with each movie.
- Retrieves additional content details such as descriptions, tag lines, and user reviews.
- Creates robust movie embeddings using BERT, enabling efficient similarity calculations.
- Recommends top movies based on prompt based user input, including movie names and IMDb rating thresholds.

## Prerequisites

To run this project, you\'ll need:

- Python 3.x
- Required Python libraries:
  - requests
  - bs4 (Beautiful Soup)
  - pandas
  - numpy
  - torch
  - transformers
## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sanjasmit/movie-recommendation-system.git
   cd movie-recommendation-system


1.Install required libraries:


```python
pip install requests 
pip install bs4 
pip install pandas 
pip install numpy 
pip install torch 
pip install transformers
```

# Usage

Run the recommendation script:


```python
python recommend_movies.py
```

Follow the prompts to input your preferences, including movie names and IMDb rating thresholds.

# Examples
1. Mention a detailed prompt( Detailed prompts will yield more relevant and better results): 
    - I want a action movie with imdb:8 ,similar to "Mission: Impossible" and "The Godfather" 
    - I want a action,adventure, thriller movie which involves war and blood shed, it should have a imdb:8

2.Mention a movie name and IMDb rating: "Mission: Impossible" imdb:8.0

3.Mention only movie names: "The Matrix", "The Godfather", "John Wick"


4.Mention IMDb rating only: imdb:7.5

# Prompt-Based Input

The quality of recommendations directly correlates with the accuracy and detail of your input prompts. The input is prosessed for sentiment analysis and the detailed description provided by the user helps in improving the output. Mentioning specific movie names within double inverted commas and specifying IMDb rating thresholds can yield more relevant and accurate recommendations.

# Author

SMIT SANJA

GitHub: github.com/sanjasmit

# Acknowledgements

This project is based on the concept of leveraging NLP and web scraping for movie recommendations. The IMDb website serves as the data source for movie information.

# License

This project is licensed under the MIT License - see the LICENSE file for details


```python

```
