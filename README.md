# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is centralized library that is used to store states throughout the whole application. Instead of multiple useStates with it's own component, you can put all of your global states in Redux and recall it whenever needed. 
```

2. What packages do we install to use Redux?

```
We need to install NPM, react-redux and redux.
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
From my understanding, redux has a unidirectional flow. As long as redux is installed and set up, you should be able to recall state from redux at any point in the application.
```

4. What do we use in order to manage different pieces of state?

```
We use reducers to break up state, actions to update state and types to define the actions done to state.
```

5. What do we use to perform an update to state?

```
We use actions to perform updates on state.
```

6. How do we access state from Redux?

```
You first put the state into redux store. You then connect store to react and call store as a prop when necessary.
```

7. In your own words, describe how to set up Redux for a React App.

```
You first have to install npm, react-redux and redux to your application. You then have to connect redux to react in your application. From there, you need to set up reducers to break up your state, actions to update state and types. With each state broken up, you can then call on one specifically when necessary. Calling one state instead of the whole state should be faster and improve efficiency.
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
