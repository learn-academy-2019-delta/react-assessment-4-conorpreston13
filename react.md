# ASSESSMENT 4: REACT ASSESSMENT
## Interview Practice Questions

Answer the following questions. First, without external resources. Challenge yourself to answer from memory. Then, research the question to expand on your answer. Even if you feel you have answered the question completely on your own, there is always something more to learn.  

1a. Indicate which of the following statements about React are false:

true - React is a modern, efficient answer to complex UI applications
false - React will only render on the server using Node.js
false - React is a full stack framework for modern web applications
true - React is a flexible library that plays the role of V in an MVC framework
false - You should always update a component's state directly using this.state
false - React is made up of encapsulated components that manage their own state
true - React components render HTML

1b. Add an interesting true fact about React to the list.

2. What are "smart" and "dumb" components? Explain the difference and also add why we bother to make the distinction between them.

  Your answer: smart holds state, dumb does not

  Researched answer:Dumb components are components that don't interact with state. All they do is receive props and call functions passed down by props. Smart components are components that do interact with state. They change state by dispatching actions and directly access the state for retrieving data.



3. When we use "yarn add ..." in the terminal - what is yarn doing? And what file will always be automatically updated after we add a package with yarn?

  Your answer: yarn allows to run specific apps. not sure about the file

  Researched answer:yarn install is used to install all dependencies for a project. This is most commonly used when you have just checked out code for a project, or when another developer on the project has added a new dependency that you need to pick up



4. How would you explain state to a friend who doesn't know code?

  Your answer: state is the current screen you look at at any given time

  Researched answer: state” is an object that represents the parts of the app that can change



5. What is the difference between component state and props? Your answer should include a short explanation of both.

  Your answer: state is the state of a component, props are state that is adjusted from a different component

  Researched answer:The difference is all about which component owns the data. State is owned locally and updated by the component itself. Props are owned by a parent component and are read-only. Props can only be updated if a callback function is passed to the child to trigger an upstream change
