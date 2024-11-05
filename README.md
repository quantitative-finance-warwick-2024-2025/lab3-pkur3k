[![Open in Codespaces](https://classroom.github.com/assets/launch-codespace-2972f46106e565e64193e422d61a12cf1da4916b45550586e14ef0a7c637dd04.svg)](https://classroom.github.com/open-in-codespaces?assignment_repo_id=16943995)
# IB9JHO Lab 3 - Functions and Scope
Exercises 1-4 require you to fill in all the function definitions in src/exercises.cpp.
Once you have completed that, exercise 5 is outlined below.

# Exercise 2
The Fibonacci numbers are defined:
- $F_n = F_{n-1} + F_{n-2}$
- $F_0 = 0$
- $F_1 = 1$

 
You should declare three local variables in the function; F_n, F_n_minus_1 and F_n_minus_2;
and update them in every loop iteration. Deal with the base cases first outside the loop,
then deal with $n > 1$ inside the loop.

# Exercise 5
At this point test_fib should be passing. Running the test 
benchmark_fib generates some data about the performance of the three Fibonnaci
functions and writes to build/tests/fib_benchmark.txt. For both release and debug builds,
generate and copy the results file to benchmarks/fib_benchmark_debug.txt and benchmarks/fib_benchmark_release.txt respectively.
You can change the build type in vscode from the cmake tab from the panel on the left of the screen.

Write a short interpretation of the results in benchmarks/comments.txt, commenting on the differences
in performance between the functions and the different build types.

The check_benchmark_results should pass when you have all three files in the benchmarks folder, which completes the lab.


# Test and submit
All the tests should pass when you run CTest.
Once you have confirmed this, submit your work by pushing your changes to the repository.
You can use the commit message "Submit assignment" or something similar.
