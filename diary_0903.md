# Diary 09.03.2020

## Object oriented work

* Java is an object oriented language, that means that basically everything is seen as an object. objects created in Java are abstract representations of real life objects, e.g. a cash register, a car, etc.
* a class is like a construction plan for an object
* objects can skills (=methods) and attributes. these attributes can be objects as well.
* when you create a class, you can use this as a reference datatype
* objects are generated with the keyword ```new```, like ```Scanner``` and ```Random```
* every class contains a default constructor, if not otherwise stated. example:
```java
public class Product {
    public String name;
    public Double price;
}
```
* other constructors need parameters
```java
public Product(String name, Double price) {
    this.name = name;
    this.price = price;
}
```
* the ```this``` word always refers to the current instance of a class.
* primitive datatypes cannot be null and cannot use methods
* reference datatypes can call methods like .toString
* static variables are not tied to instances, but to classes
* static variables are written in all caps, e.g. ```BON_COUNTER```, ```PERSON_COUNT```, ... 
* not static variables are tied to objects 