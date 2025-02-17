# TrustySort Java Algorithms

1.[Description](#description)

2.[Method calls](#Methods-Calls)

3.[Installation Guide](#instalation-guide--dependencies)

6.[About](#about)

## Description
-------------
This library provides efficient implementations of various sorting algorithms, designed to facilitate the organization of data in a swift and precise manner. Each algorithm has been carefully optimized to ensure fast and reliable execution, adapting to different scenarios and processing needs. With a focus on simplicity and efficiency, this tool was born to help students with their logic by giving them raw code without explanation to make them try to understand them and experiment with it, also you can use it for your own applications.

*** Disclaimer: The algorithms implemented in this library are inspired by the resources provided on [GeeksforGeeks](https://www.geeksforgeeks.org/ "GeeksforGeeks") and got a little modification specifically to ensure a proper use of all of them as methods. All credit goes to the authors and contributors of the original content. ***

## Methods Calls
| Method                             | Time Complexity                                                                                       |
|------------------------------------|------------------------------------------------------------------------------------------------------|
| bubbleSort(int[] arr)              | Best case: O(n) (nearly sorted). Average & Worst case: O(n²) (reversed list).                        |
| bucketSort(float[] arr)            | O(n + k), where n is elements and k is the number of buckets. Efficient with evenly distributed data.|
| countSort(int[] arr)               | O(n + k), where n is elements and k is the range of values. Efficient when k is small.               |
| gnomeSort(int[] arr, arr.length)   | Best case: O(n). Average & Worst case: O(n²).                                                          |
| heapSort(int[] arr)                | O(n log n) in all cases. Consistent performance, independent of input order.                          |
| insertionSort(int[] arr)           | Best case: O(n) (nearly sorted). Average & Worst case: O(n²). Efficient for small/nearly sorted data. |
| mergeSort(int[] arr, 0, arr.length - 1) | O(n log n) in all cases. Requires extra memory for recursion.                                           |
| quickSort(int[] arr, 0, arr.length - 1) | Best & Average case: O(n log n). Worst case: O(n²) (poor pivot). Efficient but depends on pivot choice. |
| radixsort(int[] arr, arr.length)   | O(nk), where n is elements and k is the number of digits/bits. Efficient when k is small.             |
| selectionSort(int[] arr)           | O(n²) in all cases. Inefficient for large lists, same number of operations regardless of order.      |

| Utility                           | Description                                                                                           |
|------------------------------------|------------------------------------------------------------------------------------------------------|
| printElements(int[] arr)          | Prints all elements of the given array.                                                               |


## Instalation guide / dependencies 
-------------
* [Java (latest)](https://www.oracle.com/java/technologies/downloads/ "Java (latest)")
* IDE of your choise to test.

In order to use it just clone the repository wherever you want and add it as a library to the project structure by adding the .jar file to your project's build path.

lastly try one method to test out, remember to import the package. 

