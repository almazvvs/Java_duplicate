# Data Types

> Headshot

Java is a statically-typed language. This means that it should know the type of each variable at compile-time. This means that you must specify the type of the variable before you can use it.

Data types define the values that variables can take. For example, if a variable has `int` type, it can only take integer values.

In Java, we have two categories of data types, primitive and non-primitive data types. In this tutorial, we'll discuss the primitive ones.

In the previous tutorial, we learned how to declare a variable.

> Presentation

```java
int x = 5;
```
Here we're making an integer variable called `x` and assigning a value of 5 to it.

In general, the syntax of creating variables can be written like this:

```java
datatype name = value;
```

You also don't have to immediately assign a value to a variable, so this works just fine.

```java
datatype name;
```

> Here the `datatype` gets transitioned to `int` and `name` gets transitioned to `x`.

```java
int x;
```

so this also works.

Now let's talk about different data types. In Java, we have eight primitive data types: `boolean`, `char`, `byte`, `short`, `int`, `long`, `float` and `double`.

`byte`, `short`, `int` and `long` data types are used for storing whole numbers.

`float` and `double` are used for fractional or floating-point numbers.

`char` is used for storing characters (single letters).

`boolean` data type is used for variables that can hold either `true` or `false`.

Let's go through each one of them.

## `byte`

This can hold whole numbers between -128 to 127.

```java
byte a = -120;
byte b = 8;
```

The size of `byte` is, wait for it, a byte!

## `short`

This can hold whole numbers between -32768 to 32767.

```java
short a = -10000;
short b = 1111;
```

The size of `short` is 2 bytes.

## `int`

This is arguably the most common primitive data type and it can hold whole numbers between -2,147,483,648 to 2,147,483,647.

```java
int a = -100000000;
int b = 1000000000;
```

The size of `int` is 4 bytes.

## `long`

`long` is usually used when int is not large enough to hold the value. `long` can hold whole numbers from -9,223,372,036,854,775,808 to 9,223,372,036,854,775,807. 

```
long a = -10000000000000L;
long b = 77777777777777L;
```

Notice that we're using an `L` at the end of our number. We need to do that to tell Java that we're making a `long` literal. The size of `long` is 8 bytes.


## `float` and `double`

These data types are used to hold floating-point numbers such as `3.14` and `-1.1`. `float` takes 4 bytes of memory while `double` takes 8 bytes of memory. The accuracy of `double` is, therefore, better and it's more common to use it instead of `float`.

```java
float pi = 3.14f;
double e = 2.71828;
```

Here you see that we ended the `float` literal with `f`. This tells Java that we're making a `float` and not a `double`.

## `char`

As you might remember from the previous video, `char` can hold characters!

```java
char yourJavaGrade = 'A';
```

## `boolean`

Booleans can hold either `true` or `false`. They are useful when we want to check for a specific condition. We will learn about those more in another tutorial.

```java
boolean a = true;
boolean b = false;
```
