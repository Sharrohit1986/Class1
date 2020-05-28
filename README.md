# Class1

## Agenda
* Installation
* Github
* Java JVM
* Packages
* Java Main
* Hello World
* Java data types
* Java Classes
* Access Modefiers
* Java Methods
* String Manipulation
* Creating Objects

## Github
Please create an account on this Site [GitHub](https://github.com) </br> You can follow me on [Author](https://github.com/su33u1411)</br> Fork Class1 Repository [Class 1](https://github.com/su33u1411/Class1)
</br>
Download Class1 Project via GIT Command
</br>
Open Terminal, Use the following commands

```
cd ./Desktop
mkdir Java_Class1
git clone <YOUR_REPOSIORTY_LINK>

```
Now you should have your own working copy.


## Java JVM
* Technical definition: The JVM is the specification for a software program that executes code and provides the runtime environment for that code.
* Everyday definition: The JVM is how we run our Java programs. We configure the JVM's settings and then rely on it to manage program resources during execution.
* Memory Management

## Packages
A package in Java is used to group related classes. Think of it as a folder in a file directory. We use packages to avoid name conflicts, and to write a better maintainable code. Packages are divided into two categories:

Built-in Packages (packages from the Java API)
User-defined Packages (create your own packages)


* Create a new Java Project on eclipse and create a new class <ClassName>.java

## Java Main
public static void main(String[] args)

Java main method is the entry point of any java program. Its syntax is always public static void main(String[] args). You can only change the name of String array argument, for example you can change args to myStringArgs.

* Create a Main method inside a Java Class

## Print a String
* Print a 'Hello World' using System.out.println()


## Java Data Types
Data Types in Java

Data types specify the different sizes and values that can be stored in the variable. There are two types of data types in Java:

* Primitive data types: The primitive data types include boolean, char, byte, short, int, long, float and double.
* Non-primitive data types: The non-primitive data types include Classes, Interfaces, and Arrays.

### Primitive data types
Primitive data types are the building blocks of data manipulation.
There are 8 types of primitive data types:
* boolean data type
* byte data type
* char data type
* short data type
* int data type
* long data type
* float data type
* double data type

- Boolean Data Type

The Boolean data type is used to store only two possible values: true and false. This data type is used for simple flags that track true/false conditions.

The Boolean data type specifies one bit of information, but its "size" can't be defined precisely.

Example: Boolean one = false

- Byte Data Type

The byte data type is an example of primitive data type. It isan 8-bit signed two's complement integer. Its value-range lies between -128 to 127 (inclusive). Its minimum value is -128 and maximum value is 127. Its default value is 0.

The byte data type is used to save memory in large arrays where the memory savings is most required. It saves space because a byte is 4 times smaller than an integer. It can also be used in place of "int" data type.

Example: byte a = 10, byte b = -20

- Short Data Type

The short data type is a 16-bit signed two's complement integer. Its value-range lies between -32,768 to 32,767 (inclusive). Its minimum value is -32,768 and maximum value is 32,767. Its default value is 0.

The short data type can also be used to save memory just like byte data type. A short data type is 2 times smaller than an integer.

Example: short s = 10000, short r = -5000

- Int Data Type

The int data type is a 32-bit signed two's complement integer. Its value-range lies between - 2,147,483,648 (-2^31) to 2,147,483,647 (2^31 -1) (inclusive). Its minimum value is - 2,147,483,648and maximum value is 2,147,483,647. Its default value is 0.

The int data type is generally used as a default data type for integral values unless if there is no problem about memory.

Example: int a = 100000, int b = -200000

- Long Data Type

The long data type is a 64-bit two's complement integer. Its value-range lies between -9,223,372,036,854,775,808(-2^63) to 9,223,372,036,854,775,807(2^63 -1)(inclusive). Its minimum value is - 9,223,372,036,854,775,808and maximum value is 9,223,372,036,854,775,807. Its default value is 0. The long data type is used when you need a range of values more than those provided by int.

Example: long a = 100000L, long b = -200000L

- Float Data Type

The float data type is a single-precision 32-bit IEEE 754 floating point.Its value range is unlimited. It is recommended to use a float (instead of double) if you need to save memory in large arrays of floating point numbers. The float data type should never be used for precise values, such as currency. Its default value is 0.0F.

Example: float f1 = 234.5f

- Double Data Type

The double data type is a double-precision 64-bit IEEE 754 floating point. Its value range is unlimited. The double data type is generally used for decimal values just like float. The double data type also should never be used for precise values, such as currency. Its default value is 0.0d.

Example: double d1 = 12.3

- Char Data Type

The char data type is a single 16-bit Unicode character. Its value-range lies between '\u0000' (or 0) to '\uffff' (or 65,535 inclusive).The char data type is used to store characters.

Example: char letterA = 'A'

## Access Modifiers
* Private
* Protected
* Public
* Static

## Java Methods
*Mutator / Void vs Accessors