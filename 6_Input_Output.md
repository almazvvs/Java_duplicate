# Input/Output

> Headshot

So far we were only using `System.out.println()` to output different texts and numbers. But programs that always just output the same thing aren't that useful. That's why we almost always want to take some sort of input from the user and then do our computation based on that input, and come back later with an output. So let's see how to get input from the user.

> LiveCode

```java
class Main {
 public static void main(String[] args) {
 int a = 5;
 System.out.println(a);
 }
}
```

As you see currently when we run this code, it just prints the number 5, boring. We can output something on the screen by printing, so how can we get input? That's right, by scanning! We can use `Scanner` to get input, in order to access `Scanner`, first we need to import it from `java.util` package. We'll learn more about packages later, in short, they're just some useful codes written by others that we can use in our code. To use a class from a package, we can `import` it on the top of our code:

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 int a = 5;
 System.out.println(a);
 }
}
```

Next, we need to make a `Scanner` object, let's call it `myScanner`, we need to do this inside the `main` method.

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 int a = 5;
 System.out.println(a);
 }
}
```

Here we made a new variable of type `Scanner` with the name `myScanner`. Then we assigned a new `Scanner` that scans from `System.in` to it. You have to remember these two lines in the future, the import and the declaration of the `Scanner`.

Now let's get an integer from the input instead of hardcoded 5 and store it in `a`. We can do that like:

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 int a = myScanner.nextInt();
 System.out.println(a);
 }
}
```

Now if we run the code, and give an input of 10, we get another 10 back. Still kinda boring. Let's build a simple calculator that gets two integers and sums them up.

So this time we need to get two integers from the input. And we can print their sum.


```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 int a = myScanner.nextInt();
 int b = myScanner.nextInt();
 System.out.println(a + b);
 }
}
```

Let's try it with 5 and 7, enter, and there, we get 12. At least we made something somewhat useful. As you might have already guessed, in order to get a `double` number we can use `myScanner.nextDouble()` instead.

```java
import java.util.Scanner;

class Main {
 public static void main(String[] args) {
 Scanner myScanner = new Scanner(System.in);
 double a = myScanner.nextDouble();
 double b = myScanner.nextDouble();
 System.out.println(a + b);
 }
}
```

So now if we input 3.5 and -1.2, we get 2.3 as expected.

> Headshot

Great! So now we can get input, try to make different simple calculators, how about one that calculates the multiplication of two numbers instead?
