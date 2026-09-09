
DAA.PRATICAL_1
Summary:-
This practical implements and compares five fundamental sorting algorithms: Bubble Sort, Selection Sort, Insertion Sort, Merge Sort, and Quick Sort. Each algorithm sorts the input array, measures the execution time, and demonstrates its working along with its time complexity. The program helps in understanding the efficiency, performance, and practical applications of different sorting techniques.

Conclusion:-
The experiment shows that different sorting algorithms have different performance characteristics. Bubble Sort, Selection Sort, and Insertion Sort are simple to implement but are less efficient for large datasets due to their O(n²) time complexity. Merge Sort and Quick Sort are more efficient, with an average time complexity of O(n log n), making them suitable for larger inputs. The choice of a sorting algorithm depends on factors such as input size, data characteristics, memory requirements, and application needs.

DAA.PRATICAL_2
Summary:-
This program demonstrates the implementation of Linear Search and Binary Search algorithms in Python. It accepts user input, searches for a given element, measures the execution time, and displays the result along with the time complexity. Linear Search checks each element one by one, whereas Binary Search works on a sorted array by repeatedly dividing the search space into two halves, making it more efficient.

Conclusion:-
The experiment shows that Binary Search is significantly faster than Linear Search for large sorted datasets, with a time complexity of O(log n) compared to O(n) for Linear Search. However, Binary Search requires the array to be sorted, while Linear Search can be applied to both sorted and unsorted data. Therefore, the choice of algorithm depends on the nature of the input data and the application's requirements.

DAA.PRATICAL_3
Summary:-
This program implements the Heap Sort algorithm in Python. It builds a Max Heap from the input array and repeatedly extracts the largest element to produce the sorted array in ascending order. The program also measures the execution time in microseconds and displays the best, average, and worst-case time complexities.

Conclusion:-
The experiment demonstrates that Heap Sort is an efficient comparison-based sorting algorithm with a consistent time complexity of O(n log n) in the best, average, and worst cases. It provides reliable performance regardless of the input order and is suitable for sorting large datasets. Although it is not a stable sorting algorithm, Heap Sort is preferred when guaranteed O(n log n) performance and constant auxiliary space (O(1)) are required.

DAA.PRATICAL_4
summary:-
The factorial program was implemented using both iterative and recursive methods. The iterative method uses a loop, while the recursive method calls itself until it reaches the base condition. The execution time, time complexity, and space complexity of both methods were compared.

Conclusion:-
both methods take O(n) time. The recursive method uses O(n) space because it stores function calls. The iterative method uses O(1) space, so it uses less memory. Therefore, the iterative method is more memory-efficient, while the recursive method is simpler to understand.

PRACTICAL-5
Summary
In this practical, the 0/1 Knapsack Problem was implemented using the Dynamic Programming technique. The objective is to select items with given weights and values while ensuring that the total weight does not exceed the capacity of the knapsack. A Dynamic Programming table is used to store the solutions of smaller subproblems and reuse them to find the optimal solution. This approach avoids repeated calculations and efficiently determines the maximum possible value. The time complexity of the algorithm is O(n × W) and the space complexity is O(n × W), where n is the number of items and W is the knapsack capacity.

Conclusion
The Dynamic Programming approach successfully solves the 0/1 Knapsack Problem by finding the combination of items that gives the maximum value within the given capacity. Storing intermediate results reduces repeated computations and makes the algorithm more efficient than a simple recursive approach. Therefore, Dynamic Programming is an effective technique for solving optimization problems such as the Knapsack Problem.

PRACTICAL-6
Summary
In this practical, the Matrix Chain Multiplication problem was implemented using the Dynamic Programming technique. The objective is to determine the most efficient order for multiplying a sequence of matrices so that the total number of scalar multiplications is minimized. Since matrix multiplication is associative, the matrices can be grouped in different ways, but each order may require a different number of operations. Dynamic Programming stores the minimum multiplication cost for smaller matrix chains and uses these results to determine the optimal order for the complete chain. The time complexity of the algorithm is O(n³) and the space complexity is O(n²).

Conclusion
The Dynamic Programming approach successfully determines the optimal order of matrix multiplication while minimizing the total number of scalar operations. By storing the results of previously solved subproblems, unnecessary repeated calculations are avoided. Therefore, Matrix Chain Multiplication using Dynamic Programming provides an efficient solution for finding the minimum multiplication cost, especially when dealing with a large number of matrices.

DAA.PRATICAL_7
Summary:-
The Making Change Problem was solved using Dynamic Programming. The program finds the minimum number of coins needed to make a given amount.

Conclusion:-
Dynamic Programming helps solve the problem efficiently by storing previous results. The program has O(n × amount) time complexity and O(amount) space complexity.

