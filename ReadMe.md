# Synthetic Data Generation for k-means

## 1. Generate synthetic data for k-means
### a. Must have more than 10 dimensions
### b. Must be more than 5K rows
### c. Strategy:
- Choose a set of 'k' means and standard deviations.
- Pass these means and standard deviations to a random points generator.
- This will automatically create 'k' clusters corresponding to the means and standard deviations.
- Ensure that the means are neither too far apart nor too close.

### d. Notes:
- Knowing the number of clusters initially can aid in validating results.
- However, feel free to devise a better solution if possible.

## 2. Implement k-means algorithm on the dataset
### a. Self-coded algorithm:
- Ensure you write the algorithm from scratch.
- Use both Euclidean and Manhattan distances as distance measures.

### b. Evaluation:
- Be prepared to explain your algorithm in detail during a viva or evaluation.
- Make sure the code is well-commented and thoroughly understood.

## 3. Vary the number of clusters
- Start with k=2 and increase the value well beyond your original number of clusters.

## 4. Report SSE for each value of k

## 5. Plot SSE versus number of clusters
- Create separate plots for Euclidean and Manhattan distances.
- Interpret your graph carefully, noting how the SSE changes before and after reaching the original number of clusters.
