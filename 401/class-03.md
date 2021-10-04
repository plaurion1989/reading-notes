# Maps, primitives, File I/O

## Primitives vs. Objects
Objects in java are slower and have bigger memory impact than the much smaller primitive type. You should choose what object you should use based on application performance requirements.

    - How much memory
    - Default Values
    - Ignore if you have no limitations
Performance of Java code depends very much on hardware that the code runs on (memory availability)

## Exceptions in Java

An exception occurs during the execution of a program that disrupts the normal flow of instructions.  Use of exceptions help to manage errors.  The exception object contains information about the error, including its type and the state of the program when the error occurred.

    - Throwable Class: stems from object superclass
        1.Error class: when error in java virtural machine occurs.
        2.Exception class: indicates that an error occured, but isn't a system problem
            * RuntimeException class: reserved for exceptions that indicate incorrect use of an API
        
Most fo the time, you throw exceptions instead of errors.

[Back to Main Page](../README.md)