# R-basic
# Vectors
## Creating a vector
x <- c(1,2,3)
cat('all values', X)

## using seq function
Y <- seq(1,5)
cat('using seq fun',Y)
 

## Types of R vectors

typeof(X)
typeof(Y)

## Character vectors
v1<- c('geeks', '2', 'hello', 57) 
typeof(v1)

## Length of R vector
length(X)
## Accessing R vector elements
#The most common is using the ‘[]’, symbol.
#Note: Vectors in R are 1 based indexing unlike the normal C, python, etc format.
v1[2]

## by passing a range of values
# inside the vector index.
Y<- c(4, 8, 2, 1, 17)
cat('Using combine() function', Y[c(4, 1)], '\n')

## Modifying a R vector
# Creating a vector
X<- c(2, 7, 9, 7, 8, 2)

## modify a specific element
X[3] <- 1
X[2] <-9
cat('subscript operator', X, '\n')

## Deleting a R vector
### Creating a Vector
M<- c(8, 10, 2, 5)

## set NULL to the vector
M<- NULL
cat('Output vector', M)

## Sorting elements of a R Vector

my_elements <- c(1:10)
sorted_element <- sort(my_elements, decreasing = TRUE)
sorted_element

## Loop over a vector
for (value in sequence) {
    code
}

## Matrices
- homogeneous data structures

A matrix is a two-dimensional array in which each element has the same mode (numeric,character, or logical). 
Matrices are created with the matrix function. The general format is
myymatrix <- matrix(vector, nrow=number_of_rows, ncol=number_of_columns,byrow=logical_value, dimnames=list(
char_vector_rownames, char_vector_colnames))
- where vector contains the elements for the matrix, 
- nrow and ncol specify the row and column dimensions, and 
- dimnames contains optional row and column labels stored in character vectors. 
- The option byrow indicates whether the matrix should be filled in by row (byrow=TRUE) or by column (byrow=FALSE). The default is by column


