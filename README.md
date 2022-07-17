# Applying-PCA-on-MNIST-Dataset

No. of training images: 60,000
No. of testing images: 10,000

Each image is 28x28 pixels. Each pixel value is between 0 to 255, which denotes the lightness or darkness of that pixel.

We will use PCA for dimensionality reduction from 784 dimesions to 2 dimesions.
The main steps are:
1. To make the data column standardized.
2. To compute the covariance matrix.
3. To compute the eigen values and vectors.
4. Pick the 2 highest eigen values.
5. Using sklearn's FacetGrid show the data spread.
