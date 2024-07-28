# R-basic

#Creating a vector
x <- c(1,2,3)
cat('all values', X)

#using seq function
Y <- seq(1,5)
cat('using seq fun',Y)
 

#Types of R vectors

typeof(X)
typeof(Y)

#Character vectors
v1<- c('geeks', '2', 'hello', 57) 
typeof(v1)

#Length of R vector
length(X)
#Accessing R vector elements
#The most common is using the ‘[]’, symbol.
#Note: Vectors in R are 1 based indexing unlike the normal C, python, etc format.
v1[2]

# by passing a range of values
# inside the vector index.
Y<- c(4, 8, 2, 1, 17)
cat('Using combine() function', Y[c(4, 1)], '\n')

#Modifying a R vector
# Creating a vector
X<- c(2, 7, 9, 7, 8, 2)

# modify a specific element
X[3] <- 1
X[2] <-9
cat('subscript operator', X, '\n')

#Deleting a R vector
# Creating a Vector
M<- c(8, 10, 2, 5)

# set NULL to the vector
M<- NULL
cat('Output vector', M)
