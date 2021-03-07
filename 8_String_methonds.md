# String Methods

> Headshot

As we mentioned before, `String` is a class, you know what else was a class? `Scanner`! With the `Scanner` class we used things like `nextInt()` and `nextLine()`. We call these methods, `String` class also has many methods, in this tutorial we're going to learn about some of them.

> Presentation

The first method we're gonna talk about is `.length()`.

```java
String s = "hello";
int len = s.length();
```

Here the variable `len` is going to hold 5.

There are also other handy methods such as `.toLowerCase()` and `.toUpperCase()` as their names suggest they change the strings to all lowercase or all uppercase respectively.

```java
String s = "Hello, World!";
System.out.println(s.toLowerCase()); // prints hello, world!
System.out.println(s.toUpperCase()); // prints HELLO, WORLD!
```

You can also concatenate two strings using `.concat()` method.

```java
String s = "hello "
String t = "world";
System.out.println(s.concat(t)); // prints hello world
```

There is an easier way to do this though, you can use the `+` operator to concatenate strings together. Let's put it all together into a nice example.

> Live Coding

Let's ask the user to enter their name, using a `println`

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner myScanner = new Scanner(System.in);
        System.out.println("What is your name?");
    }
}
```

Now let's get a `String` from the input, which should hold our user's name.

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner myScanner = new Scanner(System.in);
        System.out.println("What is your name?");
        String name = myScanner.nextLine();
    }
}
```

Now we can print a welcome message back!

```java
import java.util.Scanner;

class Main {
    public static void main(String[] args) {
        Scanner myScanner = new Scanner(System.in);
        System.out.println("What is your name?");
        String name = myScanner.nextLine();
        System.out.println("Welcome " + name + "!")
    }
}
```

OK, let's try the name `Alice`, and we get `Welcome Alice!` from the output.

> Headshot

Now we know the basics of java, you can already make interesting little applications, make sure you try to play with the things you've learned to master them!
