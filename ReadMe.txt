1. Generate synthetic data for k-means.
a. Must have more than 10 dimensions
b. Must be more than 5K rows
c. A possible strategy could be to choose ‘k’ set of means and standard deviations
and pass it to a random points generator. This would automatically create k

clusters corresponding to the means and standard deviations. Make sure that the
means are not too far and not too close.
d. It’s better that you know the number of clusters initially for validation of results.
However, it is not necessary to follow the above strategy. You could come up with
a better solution.

2. Implement k-means algorithm on the dataset.
a. You must code the algorithm yourself
b. Use euclidean and manhattan distance as distance measure (both)
c. You would have a viva or evaluation in which you would explain your algorithm,
so make sure it is well commented and you understand it well.

3. Start with value of k=2 and increase the value much more than your original number of
clusters
4. For each value of k, report SSE
5. Finally, draw a plot of SSE versus number of clusters (separately for euclidean and
manhattan distance)
Try to interpret your graph and pay careful attention as to how the SSE changes before your
original number of clusters and after it.
