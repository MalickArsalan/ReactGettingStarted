# The Basics

## Why React

React is JavaScript **library** for **building user interfaces**.  

* React is small, and it is not a complete solution. You will need to use other libraries with React to form solutions. It focuses on just one thing, which is the second part of the definition, building user interfaces

* A User interface is anything we put in fron of users to have them interact with a machine. We can use React to describe user interfacefor it. Since web browsers understand JavaScript, we can use React to describe Web user interface

### React is *Declarative*

It means, we describe user interfaces with React and tell it what we want, not how to do it React will take care of the how and translate our declarative descriptions, which we write in the React language, to actual user interfaces in the browser.  

HTML is also declarative language, but with React, we get to be declarative for HTML interfaces that represent dynamic data.

## How exactly is NOT being a framework a good thing

**Frameworks** serve a great purpose, especially for:

* Young Teams
* Startups

Working with framework, many smart design decisiions are already made for you, whic gives you clear path to focus on writting goof application level logic.

Framework **Disadvantages**:

* Limited flexibility
  * Do things a certain way
  * Hard to deviate
* Large and full of features
  * Hard to customize
  * Use the whole thing

### Why React gained popularity

* The "virtual" browser (vs DOM API )
React gives developer the ability to work with a virtual browser that is friendlier than the real browser.

* React is Just JavaScript
Means that there is a very small react API to learn, and after that, your JavaScript skills are what make you a better React developer.

* React Native
It allows you to use your same React skills to build native mobile applications

* Battle-tested
Facebook tests all the improvements and new features that get introduced to React right there on Facebook.com, whic increases the trust in the library among the community

* Declarative Language (model UI and state)
It allowed developers to declaratively describe stateful user interfaces. Means intead of coming up with steps for the transactions on their interfaces, developers just describe interfaces in terms of final state like a function.
When transaction happen to that state, React takes care of updating user interfaces

## React's Basic Concept

1. Components
   1. We describe user interface using components. Components are just as functions. In fact, simple React components are actually just plain JavaScript functions.
   2. React components recieve certain input *objects*, and the output a description of a *user interface*.
   3. We an use a single component in *multiple user interfces* (**Reusaable**), and components can contains other components (**Composable**).
   4. React component can manage a private state.
2. Reactive Updates
   When the state of a React component, the input changes, the user interface it represents, theoutput, changes as well.
   1. *React will react* to the changes in a component's state and automatically update the parts of the DOM that need to be updated.
3. Virtual views in memory
   1. Generate HTML using JavaScript
   2. No HTML template language
   3. Tree reconcilation (Virtual DOM)

### React Components

There are two types of React components functional or class components. Both can be stateful and have side effects, or they can be purely presentational. Prefer to use function components over class components

1. Function Component
2. Class Component

Both use set of **props** and **state** as their input and output what looks like HTML, but is really a special JavaScript syntax called JSX

**Note:**

* Within a components state object can be cahnges, while the props object represents fixed values.
* Props are immutable. Components can ony change thie internal state,not their properties

### JSX

JSX is not HTML
