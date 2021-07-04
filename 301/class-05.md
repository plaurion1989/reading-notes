## How would you break a mock into a component heirarchy?
draw boxes in the mock and give them all names and give subs for bigger boxes.
## What is the single responsibility principle?
A component should be set to do one thing, if it has grown bigger than that, you should create sub-components.
## What does it mean to build a 'static' version of your application?
Building a frame of the application that has no state and instead use props to interact with each component.
## Once you have a static application, what do you need to add?
Adding state that will be able to update your application as a user interacts with your app.
## What are the three questions you can ask to determine if something is state?
Does it get passed as a prop into your component?
As the page is interacted with, will it change?
Where does the data change in your application?
## How can you identify where state needs to live?
when you have data in a component that needs to update whith user activity, thats when you add state.

[Back to Main Page](../README.md)