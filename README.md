Java Lecture: Variables By niraj@ainosoft.com

 

This lecture introduces variables in Java — what they are, how to declare them, and how to use them in programs.

 

What is a Variable?

 

A variable is a container that holds a value which can be used and changed throughout a program. In Java, every variable must have a data type and a name.

 

Syntax:

 

```
dataType variableName = value;
```

 

Example:

 

```
int age = 25;
String name = "John";
double price = 99.99;
boolean isActive = true;
```

 

Data Types

 

Java has two categories of data types:

 

Primitive Types

 

- int — whole numbers (e.g., 10, -5)
- double — decimal numbers (e.g., 3.14)
- float — smaller decimal numbers
- char — single character (e.g., 'A')
- boolean — true or false
- long — large whole numbers
- short — small whole numbers
- byte — very small whole numbers

 

Non-Primitive (Reference) Types

 

- String — text values
- Arrays
- Objects
- Classes

 

Declaring and Initializing Variables

 

```
public class Main {
    public static void main(String[] args) {
        int x = 10;
        String city = "Pune";
        double salary = 45000.50;

        System.out.println(x);
        System.out.println(city);
        System.out.println(salary);
    }
}
```

 

Variable Naming Rules

 

- Must begin with a letter, underscore (_), or dollar sign ($)
- Cannot start with a number
- Cannot use Java reserved keywords (e.g., class, public, static)
- Case-sensitive (age and Age are different)
- Use camelCase for naming (e.g., firstName, totalAmount)

 

Constants

 

Use the `final` keyword to declare a constant whose value cannot change:

 

```
final double PI = 3.14159;
```

 

Type Casting

 

Java allows converting one data type to another:

 

```
int num = 10;
double result = num; // implicit casting (int to double)

double price = 99.99;
int rounded = (int) price; // explicit casting (double to int)
```

 

Practice Exercise

 

1. Declare a variable to store your name.
2. Declare a variable to store your age.
3. Declare a variable to store your favorite number as a double.
4. Print all three variables using System.out.println().

 

Video Resources

 

Watch these videos to strengthen your understanding of Java variables:

 

- [youtube:eIrMbAQSU34]
- 
- [youtube:eIrMbAQSU34]
- 
- Java Variables and Data Types: https://www.youtube.com/watch?v=siVMrTGRqs0
- Java Full Course for Beginners: https://www.youtube.com/watch?v=A74TOX803D0
- Java Programming Basics: https://www.youtube.com/watch?v=Qgl81fPcLc8

 

Navigation

 

Previous Page: [Java Introduction](http://localhost:9036/java-introduction.md) Next Page: [Java Operators](http://localhost:9036/java-operators.md) Related Docs: [Java Data Types](http://localhost:9036/java-data-types.md), [Java Syntax Basics](http://localhost:9036/java-syntax-basics.md)

 

←Previous Java Introduction
