# Genetic-Algorithm-with-Randomness-in-Changing-Environments

This is a simple simulation to see how introduction of randomness in evolution affects the fitness of the population.

Here are the assumptions made:

Population has two genes hot gene and cold gene
For hot climate hot gene is more fit
For cold climate cold gene is more fit
Top 20% of population contributes 60% of the next generation
For remaining 80%, based on if randomness is added or not each crossover produces one child
Population is kept fixed from generation to generation in the first version

## Results

It is noted that randomness plays part until few generations. The more generations that passes with either HOT or COLD climate
randomness becomes irrelevant because most of the populations would have been fit for the given climate.

If climate is to change before the population becomes at this peak fitness introduction of randomness helps population bounce back in changing climate
