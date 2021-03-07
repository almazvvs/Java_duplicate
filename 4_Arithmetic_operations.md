# Arithmetic Operators

[Headshot]

Operators are used for performing various operations on values. For example, using the `+` operator, we can add up two numbers.

[Presentation]

For example here the value of `x` will be 5 + 4 which is 9.

```java
int x = 5 + 4;
```

You can also do this with variables.

```java
int a = 5;
int b = 4;
int c = a + b;
```

Here `c` is going to hold 9 again!

Java has different kinds of operations, in this tutorial we're only showing you the arithmetic operators. Arithmetic operators are used to perform common mathematical operators like:

* Addition with `+`
* Subtraction with `-`
* Multiplication with `*`

You can also divide with `/`, however, the division of two integers always yields another integer. So of course `6 / 2` yields 3 but also `7 / 2` yields 3. `7.0 / 2` yields 3.5 though, since 7.0 is a double.

We also have a modulus operator denoted with `%`. This operator yields the remainder of the division of its two operands. For example, `17 % 5` yields 2 because if we divide 17 by 5 we get a remainder of 2.

There is also `++` and `--`. You can increment a variable by one with `++` and decrement a variable by one with `--`.

```java
int x = 4;
++x;
```

Now `x` holds 5. It could also be written as `x++`:

```java
int x = 4;
x++;
```
Again `x` holds 5. Actually `++x` and `x++` are not exactly the same, `++x` first increments `x` and then passes it, while `x++` first passes x and then increments it. Look at the following example:

```java
int a = 3;
int b = 3;
int c = a++;
int d = ++b;
```

Here `a` and `b` both hold 4 as expected because we incremented them, however, `c` holds 3 because the increment happened after the value of `a` was assigned to `c` meanwhile `d` holds 4 since it got the value of `b` after it got incremented by one. If this feels unnecessarily complex and weird, just know that we rarely use these operators, and when we use them they're in isolation, so in our case, both `x++` and `++x` do the same thing.
