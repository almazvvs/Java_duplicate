# Strings

> Headshot

Strings are simply sequences of characters, for example, `"hello"` is a string of 5 characters. `h`, `e`, `l`, `l`, and `o`. 

> Presentation

This is how we can declare strings:

```java
String s = "hello";
```

Similar to how we did with other data types like `int` and `double`. Note that `String` is actually not a primitive data type. That's why it starts with a capital letter, stating that it's a class.

Now with the introduction of strings, we can get text input and store it in `String` objects.

> Live Coding

```java
class Main {
 public static void main(String[] args) {

 }
}
```

Let's remind ourselves about the `Scanner` class, that we discussed in the previous video. We can import it and declare one.

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 }
}
```

Now in order to read a string, we can write `myScanner.next()`. Ok let's print the same thing we got from the input.

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 String s = myScanner.next();
 System.out.println(s);
 }
}
```

Ok, now let's try to run this, and input `hello`, ok, it prints `hello` back to us!

`myScanner.next()` gets the next word, so if we enter `hello world`, it only prints `hello`. We can also get an entire line by writing `myScanner.nextLine()`:

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 String s = myScanner.nextLine();
 System.out.println(s);
 }
}
```

This time inputting `hello world` will give us `hello world` back!
