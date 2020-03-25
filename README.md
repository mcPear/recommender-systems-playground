# Recommender systems playground

[Presentation](https://docs.google.com/presentation/d/1XhmCLm7d0Nd2li6TBFxgusCa231NVxn2qK1K-CCLhOo/edit?usp=sharing)

#### About project
Repository contains implementation and comparsion of 4 basic recommender algorithms:
* **popularity based**
* **content based**
* **colaborative filtering**
* **hybrid of above**
and additionally comparsion of some KNN models and various similarity metrics. We use lot of code found on the internet.

#### Dataset
We use [Book-Crossing Dataset](http://www2.informatik.uni-freiburg.de/~cziegler/BX/) which contains about 280k users providing 1150 ratings about 270k books. Due to computational limits we use only 1k books.

#### Evaluation
We compare Jaccard Similarity between top 20 recomendations for given user returned by all implemented algorithms. Similarity between contet-based, popularity-based and collaborative filtering recomendations is low (about 0.1).
