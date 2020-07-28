# Diary 28.07.2020

## MISC

- you can call to a constructor inside another constructor. that way you have one "powerful" constructor that sets all the properties, and use it to construct objects with less known parameters, by only setting the known values and assigning a default value to unknown parameters.

## More on Lambdas

- a method consists of 4 essential parts: name, parameter list, body, return type.
- you can remove the name and the return type, because they are less important. 
- what you're left with is a lamda expression: the parameter list and the function of the method.
  ```java
  //normal method:
  Thread th = new Thread(new RUnnable() {
      public void run() {
          System.out.println("In another thread");
      }
  });
  th.start();

  //lambda method:
  Thread th = new Thread(() -> System.out.println("In another thread"));
  th.start(); 
  ```
* invokedynamic you can attach and detach to the function you want to invoke dynamically, you can attach it at runtime. 
* external iterators: normal for loop or for-each loop. 
```java
//external iterators - you control the iterations all by yourself, what is happening and why. 
for (int i = 0; i < 10; i++) {
    //code
}

for (Type variableName : arrayName) {
    //code
}

//internal iterators 
arrayName.forEach(new Consumer<Integer>() {
    public void accept(Integer value) {
        System.out.prinln(value)
    }
});

//internal iterator with lamba
arrayName.forEach((value) -> System.out.prinln(value)); 
arrayName.forEach(System.out::println); 
```

- While lambdas are really cute, keep them that way. otherwise it can become hard to read, noisy and leads to duplication and hard to test. don't make it multiple lines of code
- basically. you don't want to put actual logic in a lambda. extract the logic into an external method and then call to the method in the lambda
