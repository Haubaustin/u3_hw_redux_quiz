# Redux Quiz

<img src="https://chriscourses.com/img/blog/redux/redux.jpg" height="400px"/>

## Getting Started

- Fork and Clone

## Questions

1. What is Redux?

```
Redux is a way to store state outside of our components and access only the parts of state we need and only when we need them.
```

2. What packages do we install to use Redux?

```
react-redux and redux
```

3. In your own words, describe the flow of how Redux is used to manage state.

```
A react component has a dispatch that sends and action type and payload.  Reducers update the state in the Store with the action from the dispatch.  The updated state is sent to the component from the Store.
```

4. What do we use in order to manage different pieces of state?

```
Reducers
```

5. What do we use to perform an update to state?

```
Actions
```

6. How do we access state from Redux?

```
Wrap the app component inside the provider.
/
Accept information as props(map?).
```

7. In your own words, describe how to set up Redux for a React App.

```
- Create your react app
- Install dependencies react-redux and redux
- Create a store directory in the src folder with and index.js file
- In src/index.js import createStore and set const store to createStore that will receive the reducers as arguments.
- At bottom export default store
- In the index.js for the react-app, import { Provider }, store, and wrap the App element in a Provider element.
- Create a directory in store called reducers and create appropriate files.  
- Import, then combine reducers within create store in store/index.js to set up state for each.  
- Create file types.js and an actions folder in the store directory.
- Create a file with an appropriate name in the actions directory to define your action types and payloads.
- Reference your actions in your reducers
- Access state and actions from components by mapping to props
- Add components to App.js
```

## Submission

Pull Request due by **9AM EST** following the [PR Submission Guidelines](https://github.com/SEI-R-2-22/template_pull_request).
