# Book HTML & CSS
## Chapter 2; Text


## Chapter 10; Introducing CSS
### INSIDE the box
The first thing that chapter 10 teaches is understanding what CSS is supposed to do for you.  CSS is a language that is designed to incorperate specific rules designated to specific elements of your HTLM code.  If there is an *Element* in your HTLM file, CSS can help the Author manipulate and style that element.  They teach you to consider every element having a potential to have its own manipulatable box, depending on the authors desired outcome, can result in styling changes to your HTLM framework.

### CSS Rules and Declarations
CSS works by associating rules with HTML Elements that govern how the specified element should be displayed.  There are two parts to these rules;
- A **Sector** indicates which element the rule applies to.  there can be more than one element associated with the rule.
- A **Declaration** tells us how the element/s in the sector should be styled. 

Declarations are broken down into two parts;
- A **Property** indicates the aspect of the element that you want to change, i.e. color/font/border.
- A **Value** specifies the settings you want to use for those chosen properties, like saying exactly what color you want or exactly how big the border should be for the element.

### Using External and Internal CSS
There are two ways to impliment your CSS code into your HTML page.  External requires a seperate '.CSS' page referenced in your HTML `<head>` tag.  an example of calling your CSS rules into your HTML would look like this
> `<link href="css/styles.css" type="text/css" rel="stylesheet" />`

While using your css internally would look more along the lines of this
> `<style type="text/css">`
    body {
        font-family: arial;
        background-color: rgb(185.179.175):}
    h1 {
        color: rgb(255.255.255);}

But ***BOTH*** of these methods would produce the exact same results so long as the linked external CSS had the exact same code as the internally used CSS code.

### CSS Selectors
There are many different ways to tell elements of your HTLM to associate CSS rules to elements.  Selectors are unique and versital ways to accomplish your own personal styling touch to your entire webpage without having to code the same rule for certain elements.  a few examples in case i didnt explain that well enough are in the table below.

Selector | Meaning
---------|----------
Universal Selector | * {} Targets all elements of the page
Type Selector | h1, h2, h3 {} Targets all the `<h1>`, `<h2>`, and `<h3>` elements

# Book JavaScript and JQuery
## Chapter 2; Basic JavaScript Instructions
### Statements and Comments
> Statements are individual instructions that java uses to run on your page one by one.  Each statement should end with a semicolon.  There are usually multiple statements within a script that need to know when to be executed, thats where a code block comes in handy.

> A code block are statements surrounded by curly braces to help organize your code and run statements in order.  The curly braces are not followed with a semicolon like a statement outside of a code block would.

> Multiline comments might be needed when typing out alot of statements to help the author keep track in plain text of their thoughts.  These longer notes to self will start with `*/` and end with `*/` characters in your java file.

> Single line comments are short and sweet, only using the // characters to allow a simple note to self between writing code.

### What is a Variable?

Scripts will need to store bits of information in order to perform its task.  it can store this data in ***Variables***!

Variables can store information to later be called upon within a statement to help determine values and if arguments. The data in the variable can change everytime a script runs.

### Declaring / Assigning Value
Declaring a variable has two key parts.  First there is the variable keyword, this is what the Javascript interpreter knows to use to create a variable. 
In order to use the variable, you have to name it.  This is sometimes refered to as an identifier.  If a variable name is more than one word, coders usually write out the name in camelCase.  This means the first word is lowercase while the first letter of all other words in the name are capitalized.

Once you have created a variable and given it a name, you can tell it information that you want it to store.  This is assigning a value to the variable.

Assigning a value will require and assignment operator like an = sign followed by the variable desired value.  if you dont assign a value, the value is undefined.

### Arrays


### Expressions and Operators
An expression results in a single value, there are two types of values:
1. Just assign a value to a variable
> `var color = 'beige';`  the value of the variable is "beige"
2. Use two or more values to return a single value
> `var area = 3 * 2;` the value of the area is "6"

Expressions rely on things called operators.  These allow programmers to create a single value from one or more values.  There are many different types of operators:
> Assignment Operators assign a value to a variable `color = 'beige';`
> Arithmetic Operators perform basic math `area = 3 * 2;`
> String Operators combine two strings `greeting = 'Hi' + 'There!';`

You can not perform arithmetic when using string operators and assignment operators are the most basic form of operator.

#### Arithmetic Operators

Name | Operator | Purpose
-----|----------|--------
Addition | + | Adds one value to another
Subtraction | - | Subtracts one value from another
Division | / | Divides two values
Multiplication | * | Multiplies two values using an asterisk
Increment | ++ | Adds one to the current number
Decrement | -- | Subtracts one from the current number
Modulus | % | Divides two values and returns the remainder

## Chapter 4; Desisions and Loops
### Decisions and Conditional Statements

### Comparison Operators
> These operators have a result in **Boolean**, meaning true or false.

Operator | Meaning
---------|----------
== | is equal to
=== | is strict equal to
!= | is not equal to
!== | is strict not equal to
\\> | greater than
< | less than
\\>= | greater than or equal to
<= | less than or equal to

> There is usually one operator and two operands, operands are the valuse or variables placed on each side of the operator `3 <= 3` would return true.

### Logic Operators
> These operators allow you to compare the results of more than one comparison operator.  the best way to really describe it would to show the different logic operators and give an example.

Logic Operator | Meaning | Example
---------------|---------|----------
&& | Logical AND | `((2>6) && (4>=2))` returns true
\\|\\| | Logical OR | `((2<5) || (2<1))` returns true
! | Logical NOT | `!(2<1)` returns true

# Additional Reading Content
## Writing a Git Commit Message

Maintaining a Consise and Consistent commit message format is essential when communicating what happened while working a file or set of files.

> A well cared for log helps a projects long term success.  there are some tools to view and maintain log entries`git blame`, `revert`, `rebase`, `log`, `shortlog` and other subcommands are very useful to project team members to ensure that everyone is using the same style, content and metadata.

### The Seven Rules
1. Separate subject from body with a blank line
1. Limit the subject line to 50 characters
1. Capitalize the subject line  
1. Do not end the subject line with a period
1. Use the imperative mood in the subject line
1. Wrap the body at 72 characters
1. Use the body to explain *what* and *why* vs. *how*

[Back to Main Page](https://github.com/plaurion1989/reading-notes/blob/main/README.md)