# Diary 03.07.2020

## Exceptions

* "Checked Exceptions are the exceptions taht are checked at compile time. 
* If some code within a method throws a checked exception, then the method must either handle the exception or it must specify the exception using the ```throws``` keyword."


* "Unchecked are the exceptions that are not checked at compile time. In C++, all exceptions are unchecked, so it is not forced by the compiler to either handle or specify the exception.
* In Java exceptions under Error and RuntimeException classes are unchecked exceptions, everything else under throwable is checked.

## Static Keyword/static method

* when you define a method in a class, everytime you create an instance of this class, the method is available for this object.
* and instance method is kind of the opposite of a static method, because it is attached to the instances.
* Instance method: 
```java 
User u = new User();
u.talk();
```
* Static method: 
```java 
User.findInList();
``` 
* so static methods are call on the class directly.