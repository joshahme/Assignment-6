# Assignment-6
Doing Math in R
> A <- matrix(c(2, 0, 1, 3), ncol = 2)
> B <- matrix(c(5, 2, 4, -1), ncol = 2)
> sum_A_B <- A + B
> diff_A_B <- A - B
> print("a) A + B:")
>  print(sum_A_B)
>  print("b) A - B:")
> print(diff_A_B)
> diag_matrix <- diag(c(4, 1, 2, 3))
> print("Diagonal Matrix:")
> print(diag_matrix)
> ## [,1] [,2] [,3] [,4] [,5]
> ## [1,] 3 1 1 1 1
> ## [2,] 2 3 0 0 0
> ## [3,] 2 0 3 0 0
> ## [4,] 2 0 0 3 0
> ## [5,] 2 0 0 0 3
> custom_matrix <- diag(3, nrow = 5)
> print("Custom Matrix:")
> print(custom_matrix)
