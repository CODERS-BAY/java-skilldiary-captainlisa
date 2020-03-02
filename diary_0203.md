# Diary 02.03.20

## Methods
* for void return type, the method can only execute the code within the method, but it cannot give back a value.
* for other return types, like ```String```, ```Interger```, etc. the method returns a value that can be used within the main method. For example store it in a variable.
* method without return type
```java
public static void bye(String name) {
    System.out.println("Tschüss " + name)
}
```
* method with return type String
```java
public static String bye(String name) {
    return "Tschüss " + name;
}
```

## Multidimensional Arrays
* ```array.length``` = length of rows
* ```secondary[i].length``` = length of columns 


##  Miscellaneous
* "I".repeat(number) repeats 
* .replace("IIIII", "V"): first string is the target and the second string is the replacement
* mark some code and press strg+alt+m : extract code to method