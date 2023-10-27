# Sorting_techniques
A. Bubble Sort allows the user to input a number of elements, and then sorts the elements in ascending order using the bubble sort algorithm. Algorithm -

Prompt the user to enter the number of elements in the array.

Create an integer array 'test_array' of size 'number' to store the elements.

Use a 'for' loop to input the elements: a. For each 'iterator' from 0 to 'number-1': i. Prompt the user to enter an element and store it in 'test_array[iterator]'.

Use nested 'for' loops for the bubble sort: a. The outer loop, with 'iterator', runs from 0 to 'number-1' (inclusive): i. The inner loop, with 'n_iterator', also runs from 0 to 'number-1' (inclusive): - Check if 'test_array[n_iterator]' is greater than 'test_array[n_iterator+1]'. - If true, swap 'test_array[n_iterator]' and 'test_array[n_iterator+1]' using a temporary variable 'temporary'.

After sorting, use another 'for' loop to print the sorted elements: a. For each 'iterator' from 0 to 'number-1': i. Print the sorted element at 'test_array[iterator]'.

End of the program.

B. Bubble sorter function- uses a separate function bubble_sorter to perform the bubble sort algorithm on the array. Algorithm

Define a function 'bubble_sorter' that takes two parameters: 'number' (the size of the array) and 'parameter_array' (the array to be sorted).

Inside the 'bubble_sorter' function: a. Declare a temporary variable 'temporary' to store values during swapping.

b. Use nested 'for' loops for the bubble sort:

i. The outer loop, with 'iterator', runs from 0 to 'number-1' (inclusive):The purpose of the outer loop is to iterate through each element of the array.

ii. The inner loop, with 'n_iterator', also runs from 0 to 'number-1' (inclusive): The purpose of the inner loop is to compare adjacent elements and swap them if necessary. Check if 'parameter_array[n_iterator]' is greater than 'parameter_array[n_iterator+1]'. If true, swap 'parameter_array[n_iterator]' and 'parameter_array[n_iterator+1]' using the 'temporary' variable.

c. After sorting, use a 'for' loop to print the sorted elements:

i. For each 'iterator' from 0 to 'number-1': Print the sorted element at 'parameter_array[iterator]'.

In the 'main()' function:

a. Prompt the user to enter the number of elements ('size') and create an integer array 'test_array' of size 'size'.

b. Use a 'for' loop to input the elements:

i. For each 'iterator' from 0 to 'size-1': Prompt the user to enter an element and store it in 'test_array[iterator]'.

c. Call the 'bubble_sorter' function to sort the 'test_array' array.

End of the program.
