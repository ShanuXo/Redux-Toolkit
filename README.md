                                                            #Redux Toolkit

WHY REDUX?
    -If you want to manage the global state of your application in a predictable way,redux can help you.
    -The patterns and tools provided by Redux make it easier to understand when,where ,why, and how the state in your application is being updated and how your app logic will behave when those changes occur.
    -Redux guides you towards writing code that is predictable and testable, which give you confidence that your application will work as expected.

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

