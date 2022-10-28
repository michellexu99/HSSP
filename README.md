# Introduction to the HSSP
The HSSP method is a new method to identify the power grid topology, which can realize the recognition of multi-level power grid topology. Compared with other methods, its advantages are fast recognition speed and high accuracy.


*Related technologies：Subset sum algorithm, conservation of energy, graph theory*

# The data set
In the “Dataset” folder are five exl files, which are digitizations of the grid topology with 13,33,63,93,123 nodes, to verify the performance of the algorithm with different numbers of nodes.

# HSSP algorithm code
The whole algorithm is divided into the following five parts:
 * input data：
 Input the data required by the experiment and change its format to make it suitable for use in the algorithm; At the same time, in this part, we can change the error size of the input and observe the impact of the error on the experimental results.
  * Dynamic programming：Subsets and the core implementation method of the algorithm, but compared with the traditional dynamic programming, which stops at the first qualified result, we improve the algorithm to output all qualified results.
  * hssp：Compared with traditional subsets and methods, HSSP algorithm can realize multi-level topology identification.
  * Accuracy of verification results：In this part, the accuracy and operation time of the algorithm results are verified.
  * Shuffle the parent node list：If we want to observe the recognition accuracy in the case of node disorder, the order of the parent nodes is disrupted in this part.
  
# Example
In the example folder is a simple example.
