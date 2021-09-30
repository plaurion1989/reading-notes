# Java Basics
### Reddit Thread Takeaway
Compiling code is the process of turning the higher level languages (Java, C#, etc.) into machine language(1's and 0's) .  Just because your code successfully compiles, doesn't necessarily mean that your code will work.  you can make it the right shape, but your solution could still be incorrect.
### XKCD: Compiling TakeAway
Fun comic that demonstrates workplace downtime due to compiling code.
### Reading Java Documentation Takeaway
Reading through these step-by-step instructions makes me believe that finding the documentation on all 4200+ programs will be a breeze.  However, interpreting that information into practical use will be a different challenge all together.
## The Java Tutorials
### Language Basics
* Variables~

The **var** keyword can be used for variable naming conventions.

Instance variables are also known as non-static fields(individual state) because their values are unique to each object

Class variables are declared with the ***static*** modifier, telling the compiler there is one copy of this regardless of how many times it has been instantiated.

Local Variables are only visible to the methods where they are declared, not to the rest of the Class.

Parameters are always classified as variables, not fields.
#### Primitive Data Types
1. byte; 8 bit, useful for saving memory in large arrays
2. short; 16 bit, also useful for saving memory
3. int; 32-bit, use the Integer class to use int data type as na unsigned integer
4. long; 64-bit use this when int doesnt do the trick
5. float; 32-bit, never use this for precise values like money
6. double; 64-bit, for decimal values and still not for precise values like money
7. boolean has only two possible values; true and false
8. char; 16-bit

Data Type | Default Value
------------|-------------
byte | 0
short | 0
int | 0
long | 0L
float | 0.0f
double | 0.0d
char | "\u0000"
String (any object really) | null
boolean | false



[Back to Main Page](../README.md)