# Evolution

* A class of algorithms based on population-based search which can be used instead of gradient descent when gradient is not available
* Evolutionary algorithms (EAs) incorporate information from previous steps through the following mechanisms:
  * Fitness-based selection, which favors solutions that perform better according to a predefined fitness function.
  * Modifying existing solutions, either by mutating a current solution or recombining two solutions
* Over time, solutions evolve based on cumulative "experience" (the performance of prior generations), leading to increasingly fit solution	

# Neuroevolution
* Each solution (policy) represented as neural network
* Limitations: Neuroevolution requires a lot of weights to be optimized – evolved networks have to be small 

# Neuroevolution of Augmenting Topologies (NEAT) (Stanley and Miikkulainen, 2002)

* Evolves topology and weights of a neural network
* Evolve population of chromosomes, each represented by a graph; each node in the chromosome represents a neuron; edges are weights

# Evolving deep neural networks (Miikkulainen et al. 2024)

* Coevolutionary optimization of components, topologies, and hyperparameters
* Construct a DNN from a DeepNEAT chromosome by traversing chromosome graph
* Evaluate DNN by training and measuring network performance using fitness
* Limitations of DeepNEAT: resulting DNNs are complex and unprincipled (they lack structure)
* CoDeepNeat: Extension of DeepNEAT by coevolution of modules and blueprints
  * Key idea: many DNNs have repetitive “modules” – modularity leads to structured network design
  * Evolve two population of modules and blueprints separately using the same methods:
    * Blueprint chromosome: graph with pointers to modules
    * Module chromosome: layers stacked in a common pattern 




