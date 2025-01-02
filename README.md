## The problem Context

This model was developed as a solution to a Data Challenge presented by a multinational beverage company.

The problem is described as this:

*The logistics department wants to improve the delivery system by smartly allocating delivery resources.

As part of this effort, they would like to predict the number of order days in the month for each user, and
they want to be able to perform this prediction at every point of the month.

An example of the data is given bellow:

![./resources/example_data.png](Dataset example)

In the example, we can see data of a user in January 2021.

This user had 2 orders on Jan' 4th and 3 orders on Jan' 25th. In total this user had 2 order days.

The exercise consists on predict the number of order days in August 2022*


The challenge consisted on two questions that were developed in this ![./negative_poisson_modelling_supply_optimization.ipynb](notebook):

1. Build a model for predicting the number of order days for the mentioned month
2. Explaining the theoretical foundation underlying the data prior-distributions and model choices.

Enjoy!


**Disclaimer:** Even tough the data is supposed to be synthetic, I preferred not sharing it