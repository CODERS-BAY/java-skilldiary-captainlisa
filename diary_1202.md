## Diary 12.02.2020

### The Wondrous World of Arrays
* Arrays are used to store **multiple values in a single variable**. That saves the work of declaring seperate variables for each value you need. 
* An array for colors would look like this:
```java
String[] color = {"red", "blue", "green", "yellow", "purple"};
```
* Every single value of the array has an index number that start with [0], [1], [2], [3], ... [n]. So **0 is the first element**, 1 the second, and so on.
* By referring to the index number, you can access an element from the array.
* You can also change an array element by referring to the index number:
```java
color[0] = "orange";
```
* Now, the output for ```System.out.println(color[0]);``` would be "orange" and not "red"
* By accessing ```color.length``` you can find out how many elements are in an array
* There are also multidimensional arrays, where you can store more than one array in one variable:
```java
int[][] numbers = { {1, 2, 3, 4}, {5, 6, 7} };
```
* you can also let arrays "grow". technically, an array has a fixed length that cannot be changed later on. but with the use of a second array and a for loop, you can technically overwrite the shorter with the longer array. Here is a code example:
```java
while (!scan.hasNext("q") || scan.hasNext("Q")) {
            int newValue = scan.nextInt();
            int[] newArray = new int[numbers.length + 1];
            for (int i = 0; i < numbers.length; i++) {
                newArray[i] = numbers[i];
            }
            newArray[numbers.length] = newValue;
            numbers = newArray;
        }
```

## Algorithms for sorting
* Selection sort divides the array in two sections, one sorted and one unsorted and checks every single index of the array for the shortest (or biggest number, depending on how you want to sort it)
