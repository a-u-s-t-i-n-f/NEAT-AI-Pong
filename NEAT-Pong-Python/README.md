# NEAT-Pong-Python
Using the NEAT algorithm to train an AI to play pong in Python!


What neat is going to do is create a bunch of neural networks 
with predefined hidden layers and hidden nodes
    we start with population of neural networks(genomes) - 10
    they will all be slightly different

    number of input and output nodes will stay the same

    what will change is hidden nodes, connections, and parameters

we will take genomes and test their fitness because this is a genetic algorithm

fitness is how well they complete their designated tasks
    test will be how well the ai hits the ball

The genomes with the highest fitness score will then be saved while the others are discarded

the highest scored genomes will be bred to for the next generation
    breed best networks to get a better offspring

    we continue this process until we find a neural network that meets our criteria

in config.txt, fitness_threshold will be when breeding and algorithm stops
    pop_size determines how long the ai will take to learn

if you switch feed_forward to False you get a recurrent neurla network which means output of previous call to neural network is going to bean input to the next call to save "history" of neural netowrk