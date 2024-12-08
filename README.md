# Homework 4 - Algorithmic Methods of Data Mining

## Movie Recommendation System 

![Movie Recommendation](https://www.justwatch.com/appassets/img/home/global-home-bg-comp.png)

This repository contains the solution for **Homework 4** of the course *Algorithmic Methods of Data Mining*.

---

## Description of Homework
The goal of this project is to design and implement a recommendation system for the entertainment industry using the [*MovieLens dataset*](https://www.kaggle.com/datasets/grouplens/movielens-20m-dataset?select=rating.csv). This system focuses on two key objectives:  

1. **Recommendation System with LSH**: Locality-Sensitive Hashing (LSH) will be employed to efficiently identify users with similar movie preferences and recommend movies based on their viewing and rating behavior;
2. **User Segmentation**: Using unsupervised clustering models (Kmeans and Kmeans++) to group users based on similar movie preferences, enabling personalized recommendations.

## Description of an Algorithm based on strategy game
In addition to creating a user preference recommendation system, the computational complexity of an algorithm based on a strategy game will be implemented and analyzed. A brief description follows:
- In this strategic number game, Arya and Mario face off over a sequence of numbers. Alternating turns, they select either the first or last number from the sequence, adding its value to their score. With each strategic choice, they aim to maximize their total while minimizing their opponent's potential. 
- The game continues until all numbers are claimed, and the highest total score determines the winner.
  
---

### Examples:

**Input 1**

```nums = [1, 5, 2]```

**Output 1**

```False```

**Explanation:** Arya’s optimal choices still lead her to a lower score than Mario’s, so she cannot guarantee victory.

**Input 2**

```nums = [1, 5, 233, 7]```

**Output 2**

```True```

**Explanation:** Arya, by playing perfectly, can ensure she ends up with the highest score.

---

### Repository Contents:

# Movie Project

This folder contains a notebook file with the progress and comments of the tasks performed, and several `.py` files of the functions implemented for various tasks. Specifically, it includes:

## Files:

# Movie Project

This folder contains a notebook file with the progress and comments of the tasks performed, and several `.py` files of the functions implemented for various tasks. Specifically, it includes:

## Files:

- **Movie Dataset Analysis.ipynb**: A Jupyter Notebook containing Python code, explanations, and outputs for each question of the homework, along with pseudocode for an algorithm. The computational complexity is analyzed and compared with that of an LLM response model.

- **locality_sensitive_hashing.py**: A Python file that implements the Locality Sensitive Hashing (LSH) algorithm. It builds hash buckets based on MinHash signatures to efficiently identify similar items, supports querying for similar users, and includes tools for debugging bucket distributions.

- **minhash_similarity.py**: A Python file implementing the MinHash algorithm to generate signatures for sets and estimate their Jaccard similarity. It supports linear, polynomial, and universal hash functions and provides functionality to create MinHash signatures and compare similarity between sets.





