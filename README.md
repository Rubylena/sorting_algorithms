# Sorting algorithms & Big O :computer:


## Introduction :mag:

A Sorting Algorithm is used to rearrange a given array or list elements according to a comparison operator on the elements.

---

## Projects :open_file_folder:

1. [bubble_sort](./0-bubble_sort.c)
1. [insertion_sort_list](./1-insertion_sort_list.c)
1. [quick_sort](./3-quick_sort.c)


## Type algorithms :space_invader:

  - Selection Sort.
  - Bubble Sort.
  - Recursive Bubble Sort.


## 0. Bubble sort :nut_and_bolt:
* Write a function that sorts an array of integers in ascending order using the Bubble sort algorithm

## 1. Insertion sort :electric_plug:
* Write a function that sorts a doubly linked list of integers in ascending order using the Insertion sort algorithm

## 2. Selection sort :hammer:
* Write a function that sorts an array of integers in ascending order using the Selection sort algorithm

## 3. Quick sort :hocho:
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm

## 4. Shell sort - Knuth Sequence
* Write a function that sorts an array of integers in ascending order using the Shell sort algorithm, using the Knuth sequence

	* Prototype: void shell_sort(int *array, size_t size);
	You must use the following sequence of intervals (a.k.a the Knuth sequence):
		* n+1 = n * 3 + 1
		* 1, 4, 13, 40, 121, ...
## 5. Cocktail shaker sort
* Write a function that sorts a doubly linked list of integers in ascending order using the Cocktail shaker sort algorithm

 * Prototype: void cocktail_sort_list(listint_t **list);
 * You are not allowed to modify the integer n of a node. You have to swap the nodes themselves.
 * You’re expected to print the list after each time you swap two elements (See example below)

## 6. Counting sort
* Write a function that sorts an array of integers in ascending order using the Counting sort algorithm
 * Prototype: void counting_sort(int *array, size_t size);
 * You can assume that array will contain only numbers >= 0
 * This array is of size k + 1 where k is the largest number in array

## 7. Merge sort
* Write a function that sorts an array of integers in ascending order using the Merge sort algorithm
 * You must implement the top-down merge sort algorithm
  * When you divide an array into two sub-arrays, the size of the left array should always be <= the size of the right array. i.e. {1, 2, 3, 4, 5} -> {1, 2}, {3, 4, 5}
  * Sort the left array before the right array

## 8. Heap sort
* Write a function that sorts an array of integers in ascending order using the Heap sort algorithm
 * You must implement the sift-down heap sort algorithm

## 9. Radix sort 
* Write a function that sorts an array of integers in ascending order using the Radix sort algorithm
 * Prototype: void radix_sort(int *array, size_t size);
 * You must implement the LSD radix sort algorithm
 * You can assume that array will contain only numbers >= 0

## 10. Bitonic sort
* Write a function that sorts an array of integers in ascending order using the Bitonic sort algorithm
 * You can assume that size will be equal to 2^k, where k >= 0 (when array is not NULL …)

## 11. Quick Sort - Hoare Partition scheme
* Write a function that sorts an array of integers in ascending order using the Quick sort algorithm
 * You must implement the Hoare partition scheme.
 * The pivot should always be the last element of the partition being sorted.

## 12. Dealer
* Write a function that sorts a deck of cards.
 * Each node of the doubly linked list contains a card that you cannot modify. You have to swap the nodes.
 * You can assume there is exactly 52 elements in the doubly linked list.
