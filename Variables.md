# Variables

> Headshot

A variable is a name that is associated with a value. 

> Presentation

```java
int x = 5;
```

Here I declared a variable called `x`. `int` is the type of the variable meaning that it's of type *integer* which can hold, well, integers like -4, 0, or in this case 5.

`int` is not the only type of variable, for example, we can have:

```java
char myCharacter = 'A';
```

Here we made another variable named `myCharacter` of type `char` with a value of `'A'`.

As the name *"variable"* suggests, we can later change the value of these variables. 

```java
char myCharacter = 'A';
myCharacter = 'B';
```

now `myCharacter` has a value of `'B'`.

You might have noticed that we named out the variable `myCharacter` and not `my character`. That's because we can't use spaces inside the variable name.

There are other rules for naming variables, for example, we can't start the name with a number.

When writing Java code, we usually want to follow a style known as *`CamelCase`*. Specifically *`lowerCamelCase`*.

lowerCamelCase works like this:

* If the name of the variable is only one word, just write it in lowercase letters like `cake` or `pie`.
* When writing multi-word names, start with the first word written all in lowercase, and then add each word capitalized.

For example: `my tasty chocolate cake` becomes:

> Show this step by step in the presentation.

```java
my
myTasty
myTastyChocolate
myTastyChocolateCake
```

> Headshot

Did you guess why it's called CamelCase? It's because the capitalized letters in the middle of the name resemble camel humps!
