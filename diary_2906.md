# Diary 29.06.2020

## Typecasting and Inheritance

* working with different classes and inheritance, you can cast one object into another type.
```java
//super class: Shape 
//class Rectangle extends Shape

Shape cubert = new Rectangle();
((Rectangle) cubert).getWidth();  
```
* the main difference between interfaces and classes is, that another class can only ever inherit from one class, but a class can implement many interfaces.
* with ```instanceof``` you can check if an object belong to a certain class.