# React Native: Handling 'undefined' or 'null' Prop Values

This repository demonstrates a common issue in React Native development: unexpected null or undefined prop values in components.  This is frequently caused by asynchronous data fetching or inconsistent prop passing. The example showcases the problem and provides a clear solution using optional chaining and nullish coalescing.

## Problem

The `bug.js` file illustrates a scenario where a `FlatList` attempts to render before its data has fully loaded, resulting in an error. This is a common occurrence with asynchronous operations.

## Solution

The `bugSolution.js` file demonstrates how to elegantly handle potential null or undefined props using optional chaining (`?.`) and nullish coalescing (`??`). These operators provide a concise and safe way to access properties and provide default values when needed.

## How to Run

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install`.
4. Run `npx react-native run-android` (or `npx react-native run-ios` if you're on iOS).