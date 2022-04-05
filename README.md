# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a standalone library that can be use with other languages to manage application state.
```

2. What packages do we install to use Redux?

```
npm i react-redux redux
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
The UI triggers action/events, which get pass into the reducer. The reducer process the action and return the new state back to the UI.
```

4. What do we use in order to manage different pieces of state?

```
We use the Store and reducers to manage different pieces of state.
```

5. What do we use to perform an update to state?

```
We use the reducer functions to update state
```

6. How do we access state from Redux?

```
we need to dispatch an action to pass it through the reducer to access state.
```

7. In your own words, describe how to set up Redux for a React App.

```
To setup Redux in React App, we need to
- npm install react-redux and redux.
- import Provider from react-redux and surround app with it.
- create store directory in src. Inside store we need to create directory for actions, and reducers and a types.js.
- In types.js define the ActionTypes
- In reducers directory define the app initial state, and reducer functions.
- In action direction create a file to declare payloads for each action type.
- In store directory create index.js, inside index.js import createStore and create a new store function.
- In react app create mapStateToProps, and mapActionsTo props function.
- connect react with redux with the connect medthod imported from react-redux
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
