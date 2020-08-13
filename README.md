# Power_Iteration
Power iteration is an eigenvalue algorithm: given a covariance matrix, the algorithm produces the eigenvector corresponding to its greatest eigenvalue.

The program cov.c creates a covariance matrix from an input file. The program receives two filenames as command-line arguments. The 1st refers to the input
file, and the 2nd is the output file. The input file is a matrix, and the output file produced contain its covariance matrix.

The program eigen.c receives two command-line arguments. The 1st is the input file, the 2nd is the output file. The input file is a symmetric matrix,
and the output file produced contain its eigenvector obtained using power iteration.
