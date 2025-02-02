# TrustySort Java Algorithms

1.[Description](#description)

2.[Method calls](#Methods)

3.[Installation Guide](#instalation-guide--dependencies)

6.[About](#about)

## Description
-------------
This library provides efficient implementations of various sorting algorithms, designed to facilitate the organization of data in a swift and precise manner. Each algorithm has been carefully optimized to ensure fast and reliable execution, adapting to different scenarios and processing needs. With a focus on simplicity and efficiency, this tool was born to help students with their logic by giving them raw code without explanation to make them try to understand them and experiment with it, also you can use it for your own applications.

** Disclaimer: The algorithms implemented in this library are inspired by the resources provided on [GeeksforGeeks](https://www.geeksforgeeks.org/ "GeeksforGeeks") and got a little modification specifically to ensure a proper use of all of them as methods. All credit goes to the authors and contributors of the original content. **

## Method Calls
| Method | Time Complexity | 
| ------------- | ------------- |
 | bubbleSort(int[] arr) | Best case (when the list is nearly sorted): O(n) Average case: O(n²) Worst case (when the list is reversed): O(n²) | 
 | bucketSort(float[] arr) | Best, average, and worst case: O(n + k), where n is the number of elements and k is the number of buckets. It is efficient when the data is evenly distributed across buckets. | 
 | countSort(int[] arr) | Best, average, and worst case: O(n + k), where n is the number of elements and k is the range of the values. It's efficient when the range k is small compared to n. | 
 | gnomeSort(int[] arr, arr.length) | Best case: O(n) Average and worst case: O(n²) | 
 | heapSort(int[] arr) | Best, average, and worst case: O(n log n) HeapSort has consistent O(n log n) performance and is not affected by the input order. | 
 | insertionSort(int[] arr) | Best case (when the list is nearly sorted): O(n)Average and worst case: O(n²) InsertionSort performs well for small or nearly sorted datasets. | 
 | mergeSort(int[] arr, 0, arr.length - 1) | Best, average, and worst case: O(n log n)MergeSort guarantees O(n log n) performance but requires extra memory due to recursion. | 
 | quickSort(int[] arr, 0, arr.length - 1) | Best and average case: O(n log n) Worst case (if the pivot is chosen poorly): O(n²) QuickSort is generally very efficient, but performance depends on pivot selection. | 
 | radixsort(int[] arr, arr.length)  | Best, average, and worst case: O(nk), where n is the number of elements and k is the number of digits or bits (in the case of integers). RadixSort is efficient when k is small compared to n. | 
 | selectionSort(int[] arr) | Best, average, and worst case: O(n²)SelectionSort performs the same number of operations regardless of input order and is inefficient for large lists. | 
 
 | Utility | Description | 
| ------------- | ------------- |
| printElements(int[] arr) | print all elements with the array given| 


## Instalation guide / dependencies 
-------------
* [Java (latest)](https://www.oracle.com/java/technologies/downloads/ "Java (latest)")
* IDE of your choise to test.

In order to use it just clone the repository wherever you want and add it as a library to the project structure by adding the .jar file to your project's build path.

lastly try one method to test out, remember to import the package. 

