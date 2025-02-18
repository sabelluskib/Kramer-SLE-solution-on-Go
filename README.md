# Kramer-SLE-solution-on-Go
Implementation of Cramer's method for solving systems of linear algebraic equations in Golang

# How it works

The algorithm uses the generalized Gauss method for calculating the determinant. The Big library is also used to handle values larger than float64. If this is not used, the algorithm will stop working after about 175x175 matrix

# How to run

## single_thread

1. `apt-get install golang`
2. Generate the required matrix using the `generate.go` program. For example, a 20000x20000 matrix is generated on Apple M1 for about an hour, the generated file weighs about 1 gigabyte
3. `go run kramer_single_thread.go`

## multi_theread

1. Generate the required matrix using the `generate.go`
2. `go run kramer_single_thread.go`



