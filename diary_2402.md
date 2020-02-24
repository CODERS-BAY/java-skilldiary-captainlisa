## Diary 24.02.20

### Methods and Recursion
* Methods are used to structure a code and to outsource certain parts of a code. If you outsource something into a method, you're able to repeat this later again in an easy way.
* strg+alt+m: extract method
* strg+p: copy a line downwards
* Math.floor(calculation) = round down
* Math.ceil(calculation) = round up
* recursion needs a breaking condition (`return`) - aka when it is allowed to stop
* a method consists of an Access Modifier(`public`), a Static Modifier(`static`), a Return-type(`void`),. the name of the method (`sayBye`) and the parameters that can be added (`String name`)

```java
public static void sayBye(String name) {
    System.out.println("Bye " + name + "!");
}
```
* you call a method like this:
```java
public static void main(String[] args) {
    sayBye("Pia");
}
```
in this case the output would be: `Bye Pia!`
