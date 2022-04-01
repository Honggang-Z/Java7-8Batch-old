# Day 3 Homework
## Data types
>| Data types | Definition |
>| ------ | ------ |
>| **byte** | An **8-bit** signed two's complement integer. Its value-range lies between -128 to 127 (inclusive). Its default value is 0. |
>| **short** | A **16-bit** signed two's complement integer. Its value-range >lies between -32,768 to 32,767 (inclusive). Its default value is 0. |
>| **int** | A **32-bit** signed two's complement integer. Its value-range lies between - 2,147,483,648 (-2^31) to 2,147,483,647 (2^31 -1) (inclusive). Its default value is 0. |
>| **long** | A **64-bit** two's complement integer. Its value-range lies between -9,223,372,036,854,775,808(-2^63) to 9,223,372,036,854,775,807(2^63 -1)(inclusive). The long data type is used when you need a range of values more than those provided by **int**. |
>| **float** | A single-precision **32-bit** IEEE 754 floating point.Its value >range is unlimited. |
>| **double** | A double-precision **64-bit** IEEE 754 floating point. Its >value range is unlimited. |
>| **char** | A single **16-bit** Unicode character. The char data type is used >to store characters.  |
>| **boolean** | Used to store only two possible values: ***true*** and ***false***. |

## Flow control
> | Flow control | Definition |
> | ------ | ------ |
> | if | Used to check if an expression is true. If it is true, a statement is then executed. |
> | else | If the expression inside the brackets following the **if** keyword evaluates to **false**, the statement following the **else** keyword is automatically executed. |
> | switch | A selection control flow statement. It allows the value of a variable or expression to control the flow of a program execution via a multi-way branch. It creates multiple branches in a simpler way than using the combination of if and else if statements. Each branch is ended with the break keyword. |
> | case |  The **switch** keyword is used to test a value from the variable or the expression against a list of values. The list of values is presented with the **case** keyword. |
> | default | Default statement is executed when any of the **case**, in the **switch**, doesn't match the value of expression. It is optional. |
> | for | It enables us to initialize the **loop variable**, check the condition, and increment/decrement in a single line of code. |
> | do | Used in **do-while** loop. It is guaranteed that the statements inside the block are run at least once, even if the condition is not met.|
> | while | Allows code to be executed repeatedly based on a given boolean condition. |
> | break | The break statement can be used to terminate a block defined by while, for, or switch statements. |
> | continue | The continue statement is used to skip a part of the loop and continue with the next iteration of the loop. It can be used in combination with for and while statements. |
> | return | Used to complete the execution of a method. The return followed by the appropriate value that is returned to the caller. |

## Modifiers
> | Modifiers | Definition |
> | ------ | ------ |
> | public | The access level of a public modifier is everywhere. It can be accessed from within the class, outside the class, within the package and outside the package. |
> | private | The access level of a private modifier is only within the class. It cannot be accessed from outside the class. |
> | protected | The access level of a protected modifier is within the package and outside the package through child class. If you do not make the child class, it cannot be accessed from outside the package. |
> | static variable and method | ***Attributes*** and ***methods*** belongs to the class, rather than an object |
> | static block | Is used to initialize the static data member. It is executed before the main method at the time of classloading. |
> | static class | A static nested class may be instantiated without instantiating its outer class. Inner classes can access both static and non-static members of the outer class. A static class can access only the static members of the outer class. |
> | final variable and method | Attributes and methods cannot be overridden or modified |
> | final class | The class cannot be inherited by other classes |
> | abstract class | A class which is declared with the abstract keyword is known as an abstract class in Java. It can have abstract and non-abstract methods (method with the body). |
> | abstract method | The method does not have a body. The body is provided by the subclass (inherited from). |
> | synchronized | Methods can only be accessed by one thread at a time |
> | native | The native keyword is used to declare a method which is implemented in platform-dependent code such as C or C++. |
> | strictfp | Used for restricting floating-point calculations and ensuring same result on every platform while performing operations in the floating-point variable. |
> | transient | Attributes and methods are skipped when serializing the object containing them. |
> | volatile | The value of an attribute is not cached thread-locally, and is always read from the "main memory". More precisely that means, that every read of a volatile variable will be read from the computer's main memory, and not from the CPU cache, and that every write to a volatile variable will be written to main memory, and not just to the CPU cache. |

> | Access Modifier |	within class | within package | outside package by subclass only | outside package|
> | ----- | ----- | ----- | ----- | ----- |
> | Private | Y | N | N | N |
> | Default | Y | Y | N | N |
> | Protected | Y | Y | Y | N |
> | Public | Y | Y | Y | Y |

## Exception handling
> | Exception handling | Definition |
> | ------ | ------ |
> | try | The try keyword creates a try-catch statement. The try statement allows you to define a block of code to be tested for errors while it is being executed. |
> | catch | The catch statement allows you to define a block of code to be executed, if an error occurs in the try block. |
> | finally | The finally keyword is used to execute code (used with exceptions - try-catch statements) no matter if there is an exception or not. |
> | throw | The throw keyword is used to create a custom error. The throw statement is used together with an exception type. |
> | throws | The throws keyword indicates what exception type may be thrown by a method. |
> | assert | Used to define an assert statement. An assert statement is used to declare an expected boolean condition in a program. If the program is running with assertions enabled, then the condition is checked at runtime. If the condition is false, the Java runtime system throws an `AssertionError`.|

## Class related
> | Class related | Definition |
> | ------ | ------ |
> | class | The class keyword is used to create a class. A class should always start with an uppercase first letter, and the name of the java file must match the class name. |
> | package | The package keyword creates a package. |
> | import | The import keyword is used to import a package, class or interface. |
> | extends | The extends keyword extends a class (indicates that a class is inherited from another class). Inheritance. |
> | implements | The implements keyword is used to implement an interface. The interface keyword is used to declare a special type of class that only contains abstract methods. |
> | interface | An interface is a completely "abstract class" that is used to group related methods with empty bodies. |

## Object related keywords
> | Object related keywords | Definition |
> | ------ | ------ |
> | new | Used to create an instance of the class. In other words, it instantiates a class by allocating memory for a new object and returning a reference to that memory. We can also use the new keyword to create the array object. |
> | instanceof | Used to test whether the object is an instance of the specified type (class or subclass or interface). |
> | super | The super keyword refers to superclass (parent) objects. It is used to call superclass methods, and to access the superclass constructor. The most common use of the super keyword is to eliminate the confusion between superclasses and subclasses that have methods with the same name. |
> | this | The **this** keyword refers to the current object in a method or constructor. |
