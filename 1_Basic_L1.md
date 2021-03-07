# Basic Syntax

> Headshot

Congrats! You wrote your first Java code that outputs "Hello, World!" to the screen.

Every Java program consists of different classes. Classes are like blueprints for creating different things. For example a `Building` class can be a blueprint for building, well, buildings and a `Car` class can be a blueprint for building cars. We are going to look at the classes in more depth in another lesson.

Every class can have some properties and some methods. For example a `Building` class can have a height property and an area property. While a `Car` class can have other properties like `numberOfDoors` or `remainingFuel`.

Methods are actions that different classes can do. For example we can have a method called `.brake()` or `.honk()` for a car object. These methods can either return a value or not. For example a method like `calculateRemainingDistance()` can return a value based on the `remainingFuel` property. While honking doesn't return any value and just executes something.

Now that we know a little bit about classes and methods, let's have a closer look at the program and talk about each part of it.

> Presentation

```java
public class Main {
    public static void main(String[] args) {
        System.out.println("Hello, World!");
    }
}
```

Let's start from the first line.

> Highlight only this part and dim the rest.

```java
public class Main {

}
```

Every Java application must have at least one `class`. Here we have a `public` class called `Main`. `public` is an access modifier, we'll learn about those in the coming lessons.

```java
public static void main(String[] args) {
 
}
```

In the next line we have a method declaration, let's break it down:

> In general, anytime I'm breaking something down, it's a good idea to highlight the part in the video.

* `public`: Just like the one we had before the class, this means that other classes can see and run this method.
* `static`: This means that we don't need to create an object in order to run this method.
* `void`: This means that the method doesn't return anything.
* `main`: This is the name of the method, this tells JVM that this is the entry point of your program.
* `String[] args`: This is used for command-line arguments, we will cover that in a separate tutorial.

Finally, this is how we actually output the `"Hello, World!"` to the console:

```java
System.out.println("Hello, World!");
```

> Headshot

Now that you know what the different parts of the code do, try changing `"Hello, World!"` to some other text!
