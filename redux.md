# Redux

### Predictable state container for javascript applications.

Collection of all data to describe the app. App state container.

React represents the views which translates the application data into something that can be displayed on the screen and user can interact with.

Centralize all the application data into single object.

**Redux = application level state.**

### Reducer - a function that returns the piece of application state.

**Containers - smart components that connect React with Redux**

## Use containers

1. import ```connect``` from react-redux. This is the glue between React and Redux. They are separate libraries. 
   
2. ```connect``` takes a function and a component and produces a container. The container is a component that is aware of the state that is contained by Redux.

3. ```mapStateToProps``` is a special key here. It takes **a state** as an argument and it returns **an object**. 

4. Object that is returned will be available to our component as ```this.props```.