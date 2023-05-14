# Flash Cards study app

## JavaScript Flash Cards

### JavaScript Concepts

#### Data

**Variables**
**Const**
**Data Types**

- String
- Number
- bigInt
- Boolean
- NaN
- Undefined
- Symbol

#### Operators and Expressions

**Precedence**
**Parentheses**
**Assignment**
**Comparison**
**Arithmetic**
**Concatenation**
**Logical**
**Combination**
**Other**

#### Flow Control

**if... else**
**Switch**
**Loops**

- for
- for... in
- for... of
- while
- do... while
- break and continue statements

#### Arrays

**Array() Constructor**
**Literal notation**
**Split function**
**Accesing array elements**
**Modifying Arrays**
**Delete Elements**
**Array Methods**

- Pushing and popping
- Shifting and unshifting
- Slicing
- Splicing
  **Looping with Array Methods**
- Callback functions
- Reducing
- Mapping
- Spreading

#### Objects

**Making Objects**

- Literal Notation
- Constructor Function
- Class
- Object.create()
  **Modifying Objects**
- Dot Notation
- Square Brackets notation
  **Comparing and Copying**
  **Prototypes**
  **Deleting Object Properties**

#### Functions

#### Classes

#### Events

#### Asynchronous JavaScript

#### JavaScript Modules

- Modules are functions, variables, constants or classes that exist in their own '.js' file
- They are invoked by two keywords:
  _export_
  _import_
  **Export**
- _export_ is used when creating modules that need to be reused
  - _export_ vs _default export_
  - _export_
    - A _named export_ creates a module with the same name as the variable, constant, function, or class that's being exported
      > export function addOne(input) {
      > return input + 1;
      > }
  - _default export_
    -
- _import_ is used

## React Flash Cards

### React Concepts

**Building a React UI Process**

1. Break up the UI into a component hierarchy
2. Build a static version in React
3. Identify the minimal representation of UI state
4. Identify where the state should live
5. Add inverse data flow by using event handlers

**React is Declarative**

- Declarative Systems are where the programmer provides a UI state they want the system to create
- Imperative Systems are a series of steps necessary to change the state of the UI

**ReactDOM**

- _ReactDOM_ is the library that renders React components in the browser.
- _ReactDOM_ is only used in the src/main.jsx file
- The code in main.jsx passes a reference to an element from index.html to the _ReactDOM.createRoot()_ method
- This is what creates the **root** element where the entire application is rendered.
- The _render()_ method of the root object returned by ReactDOM is then called.
- By default the <App /> component is passed to it
- This component is known as the _Root Component_

**VirtualDOM**

- The _render()_ method is called automatically when the React-generated interface is updated
- _ReactDOM_ then updates the browser DOM tree to match the tree rendered by React
- This process is known as the _Virtual DOM_
- The _Virtual DOM_ (_VDOM_) doesn't directly update the the HTML DOM

#### JSX

#### Components

#### Data and Events
