# Mean-Variance-Standard Deviation Calculator

This is the boilerplate for the Mean-Variance-Standard Deviation Calculator project. 
This function utilize NumPy to compute the mean, variance, standard deviation, maximum, minimum, and sum of the rows, columns, and elements within a 3x3 matrix.

First, it check the input to ensure it contains exactly 9 digits. Then, it convert this list into a 3x3 NumPy array. Next,  calculate the desired statistics along the rows, columns, and the flattened matrix, and store them in a dictionary. Finally, return this dictionary as the output of the function. If the input list doesn't contain 9 digits, it raise a ValueError.

With this function, users can simply provide a list of 9 digits, and it will return a dictionary containing the mean, variance, standard deviation, maximum, minimum, and sum of the rows, columns, and elements within the 3x3 matrix.
