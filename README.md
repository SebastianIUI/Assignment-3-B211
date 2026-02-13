# Assignment-3-B211

1. The purpose of this project was to start performing heterogeneous data analysis using Python and the Pandas module, using real world data.

2. This program reads two datasets one containing sepal measurements and one containing petal measurements  and combines them into a single DataFrame. After combining the data, the program removes a column that has no title and computes several summary statistics to better understand the dataset.

3. The expected output for this program is:
A. A combined dataset containing sample ID, species, sepal length, sepal width, petal length, and petal width.
B. The mean of each numerical variable
C. The correlation between each numerical value
D. The standard deviation for each numerial value
E. The grouped analysis of species for part 2.
F. the mean of each variable.

5. The libraries used were pandas which was to load CSV values, combined datasets, and calculate the mean, correlation, standard deviation, and median. Os was used to construct file paths. Numpy was used to support numeric calculations.
6. Some limitations included The program assuming that both CSV files are in the same order so that rows correspond to the same samples when concatenated, and The correlation matrix is computed but not saved to a file.
