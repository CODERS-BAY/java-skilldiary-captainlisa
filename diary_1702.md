## Diary 17.02.20

### Insertion Sort
* the insertion sort is a stable sorting algorithm.
* it is suitable for smaller amounts of numbers or arrays that are already almost sorted, since it's performance is very slow.
* the array is split up into two parts--the sorted and the unsorted part. unlike the selection sort, the sorted part starts with the first value, ergo ```array[0]```. so the value of ```array[1]``` is the first unsorted.
* the algorithm takes the first value of the unsorted part and inserts it at the right sport of the sorted part. All the values after that get shifted back. For example: 
(bold numbers are the sorted part of the array)
* First iteration: [**12,** -3, 88, 0, 13, 5]
* Second iteration: [**-3, 12,** 88, 0, 13, 5]
* Third iteration: [**-3, 12, 88,** 0, 13, 5]
* Four iteration: [**-3, 0, 12, 88,** 13, 5]
* Fifth iteration: [**-3, 0, 12, 13, 88,** 5]
* Last iteration: [**-3, 0, 5, 12, 13, 88**]

### Bubble Sort
* This algorithm always checks a bubble of two values and switches them if necessary.
* after the first iteration, the biggest value is at the last place of the array. For example:
(Bold numbers mark the bubble that gets inspected)
* First iteration
   * [**12, -3,** 88, 0, 13, 5]
   * [-3, **12, 88,** 0, 13, 5] 
   * [-3, 12, **88, 0,** 13, 5]
   * [-3, 12, 0, **88, 13,** 5]
   * [-3, 12, 0, 13, **88, 5**]
   * [-3, 12, 0, 13, 5, 88] 
   * (after first iteration, this process repeats until all numbers are sorted. )

### Merge Sort and Quick Sort
* are faster, more efficient sorting algorithms for larger arrays.
* **Merge** first splits the array into the same amount of arrays as there are values in the array. e.g. if the array has the length 4 ```[0, 1, 2, 3]```, it gets split up into 4 different arrays with the length 1 ```[0]```. 
* After that, it merges them all together again, already sorted. 