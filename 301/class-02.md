# Article
When you write components in React, the methods you are able to use are called lifecycle events. These allow you to update the UI at any point during the lifecycle.

- The three stages of the components lifecycle are:

#### Mounting
This is when the component instance is created and the code is being inserted into the DOM. 
#### Updating
Anytime a component updates or has the state change then rerenders.
#### Unmounting
"componentWillUnmount" is the only lifecycle event during this phase, and refers to when components are removed from the DOM.

The constructor for a React component is called before it is mounted. If the component is a subclass you should call super(props), or else the props will be undefined.

The method static getDerivedStateFromProps() exists for rare cases when the state relies on props changing over time.

render() is the only required method in the component's class.

[Back to Main Page](../README.md)