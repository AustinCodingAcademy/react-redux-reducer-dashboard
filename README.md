### Reducers
* Create a new folder called reducers
* Create a file in this folder called index.js
* Import combineReducers from redux
* Create a reducer function for each piece of data in state.js, newComments, tasks…. etc
* Remember 2 parameters state and action. Remember to return state
* Combine the reducers and export

### Create Database
* Create a store.js file
* Import createStore from redux
* Import state from state.js
* Import reducers from reducers/index
* Create the store and export it

### Provide store to components
* In index.js remove the import of state and all use of props
* Import Provider from react-redux
* Import store from store.js
* Use Provider component to wrap App
* Give Provider a prop “store” and the value of the store

### Create Containers
* In each component that should care about data:
* Import connect from react-redux
* Create a function called mapStateToProps that takes parameter state
* Return an object. Decide what prop the component needs and this will be a key on the object
* Decide what data from state the component needs and that will be the value on the object
* Use the connect function and mapStateToProps to turn the component into a container
* Export the container

### Containers
* TransactionPanel 
* TopNav
* TasksPanel
* Comments
* Orders
* Tasks
* Tickets

### Fix App
* In App.js remove all instances of passing props 

