# Eigenfaces Analysis and Face Recognition

## Load Images Function

### Function: loadImages(path, set_number)
- Reads images from the specified path
- Returns a data matrix and corresponding labels

## Eigenfaces Training

### Steps:
1. Train the Eigenfaces method with `d = 30` using images from Set_1
2. Reconstruct a random image from Set_1 and observe the quality of reconstruction

## Reconstruction Error Analysis

### Steps:
1. Train the Eigenfaces method for 10 different values of `d` in the range [2, 200]
2. Reconstruct all images from Set_1
3. Calculate the average error `error_i`
4. Plot the error value against different `d` values

## Top Eigenvectors Visualization

### Steps:
1. Visualize the top 9 eigenvectors from the Eigenfaces method trained on Set_1
2. Comment on what the different eigenvectors represent

## Face Recognition Performance

### Steps:
1. Use the 10 different eigenfaces for face recognition on Sets 1-5
2. Create a performance plot of classification accuracy versus the number of components (d)

## Performance Analysis

### Steps:
1. Analyze performance on Set_2 and compare with other sets
2. Identify the `d` with the most stable performance across different sets
3. Choose the appropriate `d` for the model

## Image Reconstruction

### Steps:
1. Reconstruct a random image from each set (Sets 1-5) using the chosen `d`
2. Display the original and reconstructed images
3. Comment on the reconstruction quality

## Singular Vectors Visualization

### Steps:
1. Visualize the top 9 singular vectors after applying SVD on the data matrix from Set_1
2. Compare the singular vectors with the corresponding eigenvectors

## Eigenvalues and Covariance Matrix

### Steps:
1. Calculate the eigenvalues of the data matrix and the covariance matrix
2. Determine the percentage of total variance explained by each eigenvector
3. Print and comment on the variance percentage explained by each Eigenface
