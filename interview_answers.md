# Interview Answers

Be prepared to demonstrate your understanding of this week's concepts by answering questions on the following topics. These will not be counted as a part of your sprint score but will be helpful for preparing you for your endorsement interview, and enhancing overall understanding.

1. What problem does the context API help solve?

The Context API solves the problem of prop drilling into components that don't need those props. Context allows us to pass data directly into the component with the useContext hook

2. In your own words, describe `actions`, `reducers` and the `store` and their role in Redux. What does each piece do? Why is the store known as a 'single source of truth' in a redux application?

actions - the only way to change state in redux... an action is an specific action object that describe what happens {( type: , payload: )}
reducers - reducers are a way to reduce the mutable changes in state you don't want to an immutable, predictable, finite-state-machine.
store - The store is the source of truth for the app. All data is stored in a single state object.

3. What does `redux-thunk` allow us to do? How does it change our `action-creators`?

redux-thunk allows us to run async functions in redux - on default redux will run synchronously. Our action creators can take the dispatch function which will dispatch an action creator to the reducer, which will fire the actions during the dispatch, asynchronously.

4. What is your favorite state management system you've learned and this sprint? Please explain why!

I like useContext because it takes advantage of React's functional components and ability to use hooks. They make the code much simpler to read and write, in my opinion. I also like the idea of redux because I see the potential of how it can manage large application state and go back in time to see when and where state changes, I just think I need more with it and maybe to learn the newest version.
