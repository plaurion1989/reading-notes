# Introducing JAVA to your HTML Web Page

## How it all fits together
1. HTML is whats known as the *Content Layer*. This language gives your webpage it's structure and adds semantics.
1. CSS enhances HTML with rules that tell the HTML how to be presented on the webpage.  This is known as the *Presentation Layer*.
1. Javascript is the *Behavior Layer*, where you can change how the page behaves and interacts with a user.

It's best practice for inexperienced coders like myself to keep these layers in seperate files to inject into the HTML code as needed.

## Statements and Comments
> Statements are individual instructions that java uses to run on your page one by one.  Each statement should end with a semicolon.  There are usually multiple statements within a script that need to know when to be executed, thats where a code block comes in handy.

> A code block are statements surrounded by curly braces to help organize your code and run statements in order.  The curly braces are not followed with a semicolon like a statement outside of a code block would.

> Multiline comments might be needed when typing out alot of statements to help the author keep track in plain text of their thoughts.  These longer notes to self will start with `*/` and end with `*/` characters in your java file.

> Single line comments are short and sweet, only using the // characters to allow a simple note to self between writing code.

## What is a Variable?

Scripts will need to store bits of information in order to perform its task.  it can store this data in ***Variables***!

Variables can store information to later be called upon within a statement to help determine values and if arguments. The data in the variable can change everytime a script runs.

### Declaring / Assigning Value
Declaring a variable has two key parts.  First there is the variable keyword, this is what the Javascript interpreter knows to use to create a variable. 
In order to use the variable, you have to name it.  This is sometimes refered to as an identifier.  If a variable name is more than one word, coders usually write out the name in camelCase.  This means the first word is lowercase while the first letter of all other words in the name are capitalized.

Once you have created a variable and given it a name, you can tell it information that you want it to store.  This is assigning a value to the variable.

Assigning a value will require and assignment operator like an = sign followed by the variable desired value.  if you dont assign a value, the value is undefined.

[Back to Main Page](../README.md)