# Type Casting

> Headshot

Type casting is when you assign a value of one primitive type to another. We have two different types of casting:

1. Widening Casting
2. Narrowing Casting

> Presentation

Widening castings are when we convert a "smaller" type into a "larger" one. For example converting `short` to `int` or `int` to `double`. These castings happen automatically.

```java
int a = 5;
double b = a;
```

Here `b` holds 5 and it happened implicitly.

The order of widening castings is:

`byte` -> `short` -> `int` -> `long` -> `float` -> `double`

Narrowing castings on the other hand, are converting from a "larger" data type into a "smaller" one. Here the order is reveresed so:

`double` -> `float` -> `long` -> `int` -> `short` -> `byte`

And we need to explicitly tell Java to narrow the type.

```java
double b = 5.4;
int a = (int)b;
```

Here `a` holds 5 because we explicitly turned the double value of `5.4` into the integer value of `5` by putting the type into parentheses behind it.
