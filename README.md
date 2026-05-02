# CiaoDVDProject

Team members: Mengie Jean-Baptiste

Dataset Description: The dataset used for thsi project is the CiaoDVD dataset. It is a real world recommendation dataset commonly used for recommender systems.. It contains user ratings for movies/DVD's and optional trust relationsips between users.This dataset reflects realistic user behavior and contains a sparse rating matrix.

#how to install dependencies
for this movie recommendation poject, I neede to use pandas, numpy, matplotlib, seaborn, and scikit-surprise. Using !pip to install dependencies into google colab.

#how to run code

Users can run all cells sequentioally after installing dependencies.

#Results
After training the data and applying the baseline and SVD model, they showed similar performances. However, baseline achieved the lowest RSME(0.9541), while SVD had the lowest MAE(0.7400). Due to the sparsity in the dataset, complex models do not always outperform simple baselines. After also finding the precision and recall at k, I found  that at k=5, precision: 70% of the top 5 recommendations were relevant. We get around the same result when k=10. The recall also increases slightly as k increases. Overall this means that the recommendation model achieved strong top-k performance.
