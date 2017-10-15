I referenced this web site, https://github.com/cjh5414/redux-example, and
knew about redux, react app.

------------------------------------------
REDUX
------------------------------------------
 -Redux is a predictable state container for JavaScript apps.
 It helps you write applications that behave consistently, run in different environments (client, server, and native), and are easy to test. On top of that, it provides a great developer experience, such as live code editing combined with a time traveling debugger.

 -Redux evolves the ideas of Flux, but avoids its complexity by taking cues from Elm.
  Whether you have used them or not, Redux only takes a few minutes to get started with.
-------------------------------------------
-Advantages of REDUX
  (1)Predictability of outcome
    There is always one source of truth, the store, with no confusion about how to sync the current state with actions and other parts of the application.
  (2)Maintainability
    Having a predictable outcome and strict structure makes the code easier to maintain.
  (3)Organization
    Redux is stricter about how code should be organized, which makes code more consistent and easier for a team to work with.
  (4)Server rendering
    This is very useful, especially for the initial render, making for a better user experience or search engine optimization. Just pass the store created on the server to the client side.
  (5)Developer tools
    Developers can track everything going on in the app in real time, from actions to state changes.
  (6)Community and ecosystem
    This is a huge plus whenever you’re learning or using any library or framework. Having a community behind Redux makes it even more appealing to use.
  (7)Ease of testing
    The first rule of writing testable code is to write small functions that do only one thing and that are independent. Redux’s code is mostly functions that are just that: small, pure and isolated.
-------------------------------------------
-The three Principles of REDUX
  1.All the states of an application are stored in a single object tree structure within a single store.
  2.The only way to change the state is by passing an action object that describes what is happening.
  3.To specify how an action changes the state tree, the programmer must create a pure reducer.
