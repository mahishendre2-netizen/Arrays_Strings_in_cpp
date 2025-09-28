# Arrays_Strings_in_cpp
# Aim: To study and implement C++ arrays and strings.

# Tools: VS code.

# Theory:
What is an Array?

An array is a data structure that can store a fixed-size sequential collection of elements of the same type. Arrays are used to store multiple values in a single variable instead of declaring separate variables for each value. In C++, arrays are declared with a specified size, and elements are accessed using indices starting from 0.

# Key Features:
Stores elements in contiguous memory locations.

Fixed size defined at the time of declaration.

Access elements using index notation arr[i].

# Types of Arrays:
One-dimensional array: Linear collection of elements.

Multi-dimensional array: 2D arrays representing matrices.

# Program 1: Input and Display Array
Algorithm:

Declare an array of fixed size.

Use a loop to take input values from the user.

Store each input value into the array.

Use another loop to print the array elements.

# Program 2: Search for a Key in Array
Algorithm:

Start

Prompt the user to enter the size of the array n

Read the value of n

Declare an array numbers of size n

Repeat for i = 0 to n-1

Prompt the user to enter the i-th value

Read numbers[i]

Prompt the user to enter the key to be searched

Read the key

Repeat for i = 0 to n-1

If numbers[i] == key then

Print i+1 as the position of the key in the array

End

# Program 3: Reverse an Array
Algorithm:

Start

Enter the size of array

Read the size of the array and store it in variable n

Declare an array of size n

for i = 0 to n - 1

Enter the values

Read the value and store it in numbers[i]

The reversed array is:

Repeat steps for j = n - 1 to 0 (decrement by 1)

Print numbers[j]

End

# Program 4: Sum and Average of Array Elements
Algorithm:

Start

Enter the size of the array (n)

Create an array of size n

Use a loop to input n numbers from the user

Set sum = 0

Use a loop to add all numbers to sum

Print the sum

Calculate average = sum / n

Print the average

Stop

# Program 5: Find Maximum and Minimum in Array
Algorithm:

Take the number of elements from the user.

Input the elements into an array.

Initialize two variables max and min with the first array element.

Loop through the array and update max and min accordingly.

Display the results.

# String in C++
What is a String?

A string in C++ is a data type used to store and manipulate a sequence of characters such as words, sentences, or any text.

C++ provides two ways to handle strings:

C-style strings – Arrays of characters ending with a null character ('\0').

C++ string class – The string class is a part of the C++ Standard Library and offers flexible, dynamic, and user-friendly string handling with built-in functions for common operations.

# Operations:
Concatenation (joining two strings)

Substring extraction

Searching (finding a character or substring)

Comparison

Length calculation

# Program 1: String Input and Display
Algorithm:

Declare a string variable.

Prompt the user to enter a string.

Read the string using cin.

Print the string.

# Program 2: String Concatenation
Algorithm:

Declare two string variables.

Take input for both strings using cin.

Concatenate the strings using + operator.

Display the concatenated result.

# Program 3: Reverse a String
Start.

Declare two string variables: original and reversed.

Take input in the original string.

Traverse the string from the end to the beginning.

Append each character to the reversed string.

Output the reversed string.

Stop.

# Conclusion:
In this experiment, We learned how to use arrays and strings in C++ for storing and manipulating data. Arrays allow handling fixed-size collections with operations like input/output, searching, reversing, and calculating sum, average, min, and max. 














