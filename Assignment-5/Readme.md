YouTube Video: https://youtu.be/qQUGYH6HLFI

Question 4:

Briefly identify the difference between PCA and LDA
PCA and LDA are two widely used dimensionality reduction methods for data with a large number of input features. 
Both LDA and PCA are linear transformation algorithms, although LDA is supervised whereas PCA is unsupervised and PCA does not take into account the class labels.
PCA minimizes the number of dimensions in high-dimensional data by locating the largest variance.
The purpose of LDA is to determine the optimum feature subspace for class separation.

Both approaches rely on dissecting matrices of eigenvalues and eigenvectors, however, the core learning approach differs significantly. LDA is supervised, whereas PCA is unsupervised. 
PCA minimizes dimensions by examining the relationships between various features. This is accomplished by constructing orthogonal axes – or principle components – with the largest variance direction as a new subspace.
PCA generates components based on the direction in which the data has the largest variation - for example, the data is the most spread out. This component is known as both principals and eigenvectors, and it represents a subset of the data that contains the majority of our data's information – or variance.
On the other hand, LDA does almost the same thing, but it includes a "pre-processing" step that calculates mean vectors from class labels before extracting eigenvalues.
PCA
1.	Take the joint covariance – or correlation in some circumstances – between each pair in the supplied vector to create the covariance matrix.
LDA
1.	Calculate the d-dimensional mean vector for each class label.
2.	Create a scatter matrix for each class as well as between classes.

