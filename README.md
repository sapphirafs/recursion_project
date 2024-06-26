# Recursion Project



## Directory Tree:

recursion_project <br>
├─docs <br>
│ └─requirements.txt <br>
├─source <br>
│ ├─__init__.py <br>
│ ├─iterative_function.py <br>
│ └─recursive_floyd.py <br>
├─tests <br>
│ ├─__init__.py <br>
│ ├─test_performance.py <br>
│ └─test_recursive_function.py <br>
README.md

 <sub><sup>**reference to ascii tree generator at the bottom* <sub></sup>

## Description:

This package finds the shortest path between nodes in a graph matrix using using Floyd-Warshall algorithm and the inteperative Python language. 
A recursive function is implememnted and compared with the performance of an iterative function.

## How to Install using the following commands:

1. Clone the repository: *git clone https://github.com/sapphirafs/recursion_project.git*
2. Navigate to the project directory: *cd recursion_project*
3. Install the package: *pip install*

## How to Run:

Follow these steps to use the functionality within your code:

1. Import the package into your code (at the top of the file): *import recursion_project*
2. Create a graph representing the weight values between vertices.
3. Call the *recursive_floyd_algorithm(graph)* function whilst passing the graph matrix as an argument.
4. The function will return a matrix (list of lists/2d array) containing the shortest distances between every pair of vertices.

## For Example:

```python 
import recursion_project

# create the graph (2D array/list of lists)
graph = [
    [0, 5, sys.maxsize, 10],
    [sys.maxsize, 0, 3, sys.maxsize],
    [sys.maxsize, sys.maxsize, 0, 1],
    [sys.maxsize, sys.maxsize, sys.maxsize, 0]
]

# Call and print the function
result = recursion_project.recursive_floyd.recursive_floyd_algorithm(graph)
print(result)
```


 <sub><sup>*ascii file structure generator: https://sten-code.github.io/Ascii-File-Structure-Generator/*</sup></sub>
