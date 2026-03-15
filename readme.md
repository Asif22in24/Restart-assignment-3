What is JSX, and why is it used?

Ans:JSX (JavaScript XML) is a syntax extension for JavaScript that allows you to write HTML-like code inside JavaScript.

1.Makes writing UI easier and more readable.

2.Lets you combine logic and UI in one place.

3.Gets compiled into React.createElement() calls under the hood:

What is the difference between State and Props?
Ans:
state:
1.Data that belongs to the component itself
2.mutable

props:
1.Data passed from parent to child
2.immutable

What is the useState hook, and how does it work?

useState is a React hook that allows functional components to have state.

How it works

useState(initialValue) returns an array: [stateVariable, setStateFunction].

Updating state with setStateFunction re-renders the component with new value.

How can you share state between components?
Ans:
1.Lift state up

Move the state to the closest common parent and pass it down via props.

2.Context API

Share state globally across many components without prop drilling.

3.State management libraries

Like Redux, Zustand, or Recoil for large apps.

How is event handling done in React?

Ans:React uses camelCase syntax for events, not lowercase like HTML.

You pass a function reference, not a string.