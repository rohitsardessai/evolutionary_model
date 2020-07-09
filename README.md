# Crude Model of Evolution by Natural Selection

#### A very crude Python model of evolution by natural selection.

Natural selection exerts a selection pressure on a population. Genetic mutation is random (almost).<br>
At every generation, the genes that are most likely to survive are passed on to the next generation. Over time, this selection pressure causes the characteristics to slowly change. Given enough time, the successive generations change so much that they are considerably different from the initial population. This is how new species are formed. The process is called speciation.

In this model we start with a population with a fixed number of characteristics of interest. We also define an optimal curve towards which the selection pressure acts.<br>

At each generation we calculate new values for each feature in each individual.
