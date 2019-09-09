# React Component, React Hook & One-way Data Flow

## State Object

To use State Object, React has a special function "useState()". It returns two items for us in array

1. State object (getter) -> can be any thing, string or number etc
2. Updater function (setter)

const [currentStateValue,functionToSetNewStateValue] = useState(initialStateValue) => Using JavaScript Destructuring featuure.

This useState() function is called a Hook in the react. It is a stateful one that hooks this simple component into a state.

**Note:** in ReactDOM.render() function if we want to display multiple components we cas below three options:

1. Array of elements
When all elements you are rendering are coming from the same component in a dynamic way
2. div
3. React.Fragment tag
This will do exactly the same thing that the div did, but no new DOM parent will be introduced. This case is so common in React that the JSX extension has the shortcut for it instead of typing
<React.Fragment></React.Fragment>
you can type
<></>
this empty tag will compiled to the React.Fragment version.

**Note:** State in React component can only be access by that component it self
