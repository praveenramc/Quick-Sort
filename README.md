# Quick-Sort
Implementation of Quick Sort

Problem b. Comparison of sorting algorithms.
Due: 11:59 PM, Mon, Feb 2

Implement generics version of the following sorting algorithms: Merge
sort, Quick sort.  Compare their performances with each other and to
the sorting algorithm in Java's library.

Signature:
public static<T extends Comparable<? super T>> void
        sort(T[] arr, int p, int r)
// Sort arr[p..r].  Note that the description of this function
// is slightly different from the one in Java's library.
