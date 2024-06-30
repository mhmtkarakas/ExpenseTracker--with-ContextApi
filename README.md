# Expense Tracker

 This project is a spending calculator application built using React's Context API and useReducer hook. The application helps users track their expenses and manage their budget effectively.

  ### Technologies Used

  + __React__: Used to build the user interface.
  + __Context API__: Used for managing and passing the global state across the application.
  + __useReducer__: A React hook used for managing complex state logic

  ### Implementation Details

   1. Context API:
      
      + The Context API is used to create a global state that can be accessed by multiple components without the need to pass props manually through each level of the component tree.
      + A context is created to store the state of the expenses and the dispatch function from the useReducer hook.
    
   2. useReducer:

      + The useReducer hook is used to handle state changes in a more predictable manner by defining a reducer function.
      + The reducer function takes the current state and an action, and returns a new state based on the action type.
      + The initial state includes an array of expenses and a total budget.

  
  ### ScreenGif
           
    ![Expense Tracker GIF](./ExpenseTracker.gif)