# Multi-threading

By - Aryan Gupta 
      102103140

# Here's a brief description of each function:

## generate_matrices(n, size): This function generates a list of n random matrices, each with dimensions size x size. It uses NumPy's np.random.rand to create random values for the matrices and stores them in a list.

## multiply_matrices(matrices): This function multiplies a list of matrices together. It first generates a constant matrix of random values using np.random.rand(matrix_size, matrix_size). Then, it iteratively multiplies this constant matrix with each matrix in the input list using NumPy's np.dot function.

## multiply_with_threads(num_threads, matrices): This function performs matrix multiplication using multiple threads. It takes as input the number of threads num_threads to use and a list of matrices matrices. It creates threads to perform matrix multiplication in parallel, dividing the work among the specified number of threads. The threading.Thread class is used to create threads, and each thread calls the multiply_matrices function with a subset of matrices. Finally, it measures the time taken to complete the multiplication using threads and returns the elapsed time.


<img width="394" alt="image" src="https://github.com/AryanGupta30/Multi-threading/assets/100289349/a6976464-dcab-4ea6-b026-b4782080bd2c">


![Screenshot 2024-04-21 221706](https://github.com/AryanGupta30/Multi-threading/assets/100289349/91e1ec47-00e7-4a73-8034-388ff97ae522)

![Screenshot 2024-04-21 221627](https://github.com/AryanGupta30/Multi-threading/assets/100289349/954e2892-4680-4a18-91f3-adef142bcf68)
