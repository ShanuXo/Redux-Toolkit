                                                            #Redux Toolkit


Redux(redux-Toolkit) -> State Management library

WHY REDUX?
    -If you want to manage the global state of your application in a predictable way,redux can help you.
    -The patterns and tools provided by Redux make it easier to understand when,where ,why, and how the state in your application is being updated and how your app logic will behave when those changes occur.
    -Redux guides you towards writing code that is predictable and testable, which give you confidence that your application will work as expected.

 WHEN REDUX?
    (Question) When should i use redux in my react application?
    Answer : 1.You have large amounts of application state are needed in many places in the app.
             2.The app state is updated frequently over time.
             3.The Logic to update that state may be complex
             4.The app has a medium or large-sized codebase and might be worked on by many people. 

"Redux is a predictable state container for javscript apps"
i.e
1.It is for javScript apps
2.It is a State container
3.It is predictable


#Redux is for JavaScript applictaions
1.Redux is not tied to React
2.Can be used with React, Angular,Vue or even vanilla JavaScript
3.Redux is a library for React.

#ReduX is a State Container
1.Redux stores the state of your application
eg : 1.In LoginFormComponent:
    state={
        username:"",
        password:"",
        submitting:false
    }
    2.UserListComponent

    state={
        users:[]
    }
2.State of an app is the state shared by all the individual components of that app
3.Redux will store and manage the application state

eg: ApplicationComponent:
    state={
        isUserLoggedIn:true,
        username:"Shanu",
        profileUrl:"Shanu.github.com",
        onlineUsers:[],
        isModalOpened:false
    }

#Redux is predictable
Predictable in what way?

Redux is a state container
The state of the application can change,
Ex:todo list app-item(pending)-> item(completed)

In redux,a pattern is enforced to ensure all state transitions are explicit and can be tracked.So thats why the changes in application becomes predictable


#what is Redux Toolkit?
 ->Redux toolkit is the official,opionated,batteries-included toolset for efficient Redux development.
 ->It is also intended to be the standard way to write Redux logic in your application.

 #Shortcomings:
    -> configuring redux in an app seems complicated
    -> In addition to redux, a lot of other packages have to be installed to get redux to do something useful
    -> Redux requires too much boilerplate code
 Redux toolkit serves as an abstraction over redux.It hides the difficult parts ensuring you have a good developer experience. 


 REACT_REDUX :
    React-Redux is the official Redux UI binding library for react.

    React <----------->React-Redux<---------->Redux(Redux Toolkit) 


 Three Core Concepts:
  1.Store
  2.Action
  3.Reducer

  A Store : that holds the state of your application
  An Action : that describes what happened in the application
  A Reducer : which handles the action and decides how to update the state.    






Package Required :
1. npm install
2. npm i redux


