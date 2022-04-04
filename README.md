# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a place where you can store and retrieve state. Its used alone side front end frameworks like React and Angular.
```

2. What packages do we install to use Redux?

```
React-redux, redux, and redux-devtools-extension
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
The user will interact with the UI. This will dispatch an action through an event handler. The action is observed by Redux and ran through a reducer. In the reducer is were some action to the state is taking place. The reducer can modify the state which is then accessed from the UI using props.
```

4. What do we use in order to manage different pieces of state?

```
We can assign an action to the props and pass them to redux to be evaluated during the switch statement.

```

5. What do we use to perform an update to state?

```
We can use Reducers to update state. The action is ran through a switch statement which will return the modified state value.
```

6. How do we access state from Redux?

```
We can use the mapStateToProps function. It takes in state and returns the key and value pair needed.

```

7. In your own words, describe how to set up Redux for a React App.

```
First install react-redux and redux. Create a store directory that contains actions, reducers, types.js and an index.js file. The types.js is were the action are named. In the actions, define the type and payload of each function. For the reducer set up a switch statement that will look for each action by name. In the index.js export the store that contains the combined reducers.

```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
