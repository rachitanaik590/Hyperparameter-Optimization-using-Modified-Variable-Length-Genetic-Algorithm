# Hyperparameter-Optimization-using-Modified-Variable-Length-Genetic-Algorithm

This project aims at implementing an efficient variable length genetic algorithm (GA) to systematically and automatically tune the hyperparameters of a CNN and improve its performance, thus finding an optimal model in reasonable time.

The code is written in tf.keras. The repository has the following notebooks:

1. Variable_Length_GA_Modified_Implementation.ipynb - This notebook implements the variable length genetic algorithm with crossover modification. It generates specified number of models in a generation and then evolves the models though the pahses, increasing the depth in each phase. 
2. original_implementation.ipynb - This notebook implements the original variable length genetic algorithm which served as our baseline. 

This code has an integration with [weights and biases](https://wandb.ai/site). This helps in visualizing the metrics of the problem better and at run time.

