# Redux

## Action

Action is an object which describes what do you want to send to your store. Action only describes what happened.

## Reducer

Reducer is a function which takes the current state of your store and action which occured, then returns a new state of your store. Reducer describes how the application's state changes.

# API

## `getState()`

Returns the current state tree of your application.

## `dispatch(action)`

Dispatches an action. This is the only way to update the state of your application.

## `subscribe(listener)`

Adds a change listener. It will be called whenever the state tree changes.

`subscribe` returns a function that unsubscribes the change listener. 

