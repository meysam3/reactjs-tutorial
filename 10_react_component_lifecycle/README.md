### The Component Lifecycle

Each component has several "lifecycle methods" that you can override to run code at particular times in the process. Methods prefixed with **`will`** are called right before something happens, and methods prefixed with **`did`** are called right after something happens.

#### Mounting

These methods are called when an instance of a component is being created and inserted into the DOM:

- `constructor()`
- `componentWillMount()`
- `render()`
- `componentDidMount()`

#### Updating

An update can be caused by changes to props or state. These methods are called when a component is being re-rendered:

- `componentWillReceiveProps()`
- `shouldComponentUpdate()`
- `componentWillUpdate()`
- `render()`
- `componentDidUpdate()`

#### Unmounting

This method is called when a component is being removed from the DOM:

- `componentWillUnmount()`

### Other APIs

Each component also provides some other APIs:

  - `setState()`
  - `forceUpdate()`

### Class Properties

  - `defaultProps`
  - `displayName`
  - `propTypes`

### Instance Properties

  - `props`
  - `state`