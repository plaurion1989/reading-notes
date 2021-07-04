# What Is A Controlled Component?
A controlled component is one that is controlled by a parent component and maintains its own state.

## Should we wait to store the users responses from the form into state when they submit the form OR should we update the state with their responses as soon as they enter them? Why.
the first option you have to read the value before you can use it. It is more effiecient to have a an updating state as the user interacts.

## How do we target what the user is entering if we have an event handler on an input field?
You can use attributes to target the specific element, then you can use the event handler to handle that target event.

## Why would we use a ternary operator?
A ternary returns a boolean value and so if a condition is true then it will return an expression or value desired else the other expression or value desired will return.

#### rewrite statement as ternary:
`if(x===y){console.log(true)}else{console.log(false)`
`x===y?console.log(true):console.log(false)`

[Back to Main Page](../README.md)