## Diary 26.02.20

## Method to fill an Array with random numbers
```java
public static void randomFill(int[] arr) {
    Random r new Random();
    for(int i = 0; i < arr.length, i++) {
        arr[i] = r.nextInt(100);
    }
}
```

## Multidimensional Arrays
* basically an array that contains more arrays, like a table or matrix. two- and three-dimensional arrays are most common.
* for a three dimensional array with the length three, you have 9 values.
* within an array, all the data types need to be the same
```java
int[][] array = new int [3][2]; //multidimensional array with three 3 rows and 2 columns
//filling the array:
array[0][0] = 2;
array[0][1] = 3;
array[1][0] = 7;
array[1][1] = 8;
array[2][0] = 4;
array[2][1] = 9;
```