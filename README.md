# Text Classification with Genetic Algorithm

## Description

We used a dataset of movie genres and their descriptions. This dataset contains a variety of genres, but we divided it into 5 binary small datasets. We randomly selected 50 data from each genre. Thus, we had 100 examples in each dataset.

-	(comedy, horror)
-	(sport, animation)
-	(drama, sci-fi)
-	(documentary, music)
-	(crime, family)

Initially, words were randomly assigned to all individuals. Throughout the process, operations such as crossover, random word substitution are applied fitness value of individuals was increased. Afterwards, individuals' word lists were optimized with a genetic algorithm.

## Results

These are the observations we made from this data: 

- Increasing the number of genes above a certain value increases our score.
- Population size generally increases the score until it reaches a certain value, such as the number of genes.
