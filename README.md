# Principal-component-analysis-PCA-
This notebook provides detailed understanding of Principal Component Analysis.



# PRINCIPAL COMPONENT ANALYSIS
Principal Component Analysis, or PCA, is a dimensionality-reduction method that is often used to reduce the dimensionality of large data sets, by transforming a large set of variables into a smaller one that still contains most of the information in the large set.

Before understanding PCA get a clean understanding about Vectors,Matrices, Matrix Operations, Change of basis using Matrix Tranformations,Covariance Matrix, Eigen Values and Eigen Vectors.
NOTE: vectors and matrices are used in various techniques of machine learning

# Eigen Vectors and Eigen Value
1)Eigen Vectors:A non-zero vectors that changes by a scalar during linear tranformation i.e Vectors that only changes in its magnitude and not in direction during the transformation.Change will occur only in magnitude or length of the vector.

2)Eigen Value: Scalar Value by which it changes its magnitude is eigenvalue.

So basically, when we multiply the vector V with a tranformation matrix A the resulting vector is changed by constant (lambda) i.e T.V=constant.V

# What is Principal Component?
1-Creates a new set of coordinates for the data

2-Reveals the internal structure of the data that best explains the variance in data.

3-Thereby reduces the dimensionality of the multivariant dataset.

# steps in creating principal components
step 1: center the data

In order to get the new coordinate for these feature vectors, we simply subract each feature value to its mean.

step 2: Create Variance-Covariance Matrix

This is used as transformation matrix for feature vector to represent vector in new coordinate system.

step 3: Project existing feature vectors towards the maximum variance.

Multiplying tranformation matrix with feture vector which gives new vector. This will form a line of maximum variance

Step 4: Find Eignevectors and Eigen Values

Basically, finding out principal component that explains maximum variance is to find out the eigenvectors for these data points using their variance-covariance matrix. Finally find out the eigen vectors which has large eigen value compared to others .This is considered as principal component because it captures maximum variance in the data

# Check the Implementation of pca in above notebook
