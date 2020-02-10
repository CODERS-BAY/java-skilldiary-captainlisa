## Diary 10.02.2020

* **Jetbrains toolbox** is a tool to manage different version of Jetbrains software.
  
## About Variables and Naming Them
* Java is a **compiled** language. That means the code/programme must be compiled before it is executed. and IDE does that for us.
* Java is a **static** language that means that a variable has to have a datatype and cannot contain another datatype than the one that is declared. (Javascript is dynamic)
* primitive datatypes cannot be null.
* you can only use wrapper-datatypes in for example lists
* void = empty rückgabewert
* ```System.out.printf(...)``` stands for print formated. You can fill in placeholders with % to format the output. 
* there is a difference between ```x++``` and ```++x```; that expecially matters when it is used in a for-loop, for example
* namingConvention: camelCase for variables
* some rules for naming variables:
    * no unnecessary information
    * no type-encoding
    * it makes sense to use verbs for methods, e.g. ```addToBasket```

### About if-else
* for if it is import to check the specific cases first.
* the scope of a variable is always between the {} it was written in
* short version of if ("inline if"):  ```String ageState = age > 18 ? "adult" : "underage";```
  
### Using Git With IntelliJ
* Version Control (Bottom Left) -> Commit changes by clicking the green tick -> Push with Crtl+Shift+K
* works only if you open the repository with IntelliJ
* 
### Miscellaneous 
* package names only lowercase letters and period. 
* commit messages should always begin with an uppercase and a verb
* Crtl+Alt+L formats your code automatically 

### Scanner
* to import a Scanner write: ```import java.util.Scanner;``` outside of your Main class
* Example of code:
```java
Scanner scan = new Scanner(System.in);
int number = scan.nextInt();
```

### Random
* chooses a random number
* first import it with ```import java.util.Random```
```java
Random random = new Random();
        int shift = random.nextInt(26);
```

### Arrays
* is a collection of values from one datatype
* has a length that is fixed
* the sequence in which the values are listed is important


