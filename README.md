# React Native Code Challenge
This challenge is created to evaluate your programming skills and knowledge for pure Javascript and React Native. Our focus will be towards your approach for project structure, code efficiency, adherence to design, app local data management, app scalability, and app performance

## Objectives
  Using the provided Figma design screen, create a simple ToDo app which displays a list of all tasks and allows the user to complete a task

    1. Setup app structure and create necessary components as displayed in the design screens.
    2. Define local state for task data objects which can be used for Apollo client
    3. Tasks list: Retrieve data from local cache first, if not available then sync with mock server using GraphQL
    4. Complete a task: Allow tasks to be completed by clicking on the task checkbox. Mutate Apollo client state management to reflect task completion.
    5. Catch unexpected errors using Error boundaries and show the error in a overlay modal
    6. Write unit test to have 80% coverage
  Keep in mind that local cached data should be the first priority for retrieving, mutating and storing data.

## Guidelines
  ● Use latest RN version and utilize main functions like useState, useHooks
  
  ● Emphasize on component performance and mention in a comment
  
  ● Use Apollo Client statement management as a store
  
  ● Proper use of typescript with strict declarations
  
  ● Smart use of ES6 to destructuring objects
  
  ● Use Expo library which we can test with Expo simulator
  
  ● Use NativeBase.io components to support UI design
  
  ● Use React Navigation library for app navigation
  
  ● Use icons as SVG instead of PNG  
  
## Expectations

  We expect you to show your full programming capabilities by going extra miles to show how our project can be scalable and what performance elements you will use 
  to avoid expensive React calculations. We also expect to see how efficient code you write, how you add references to your code, how you adhere to UI design         guidelines and how you use other libraries to produce a solid outcome of your application.


## Deliverables
  We expect you to deliver a fully functional application with the following
  
    - [x] Public Github repository to access your code
    - [x] A well-structured README file describing your solution approach and how to run the application and test cases
    
## Technical Stack
React native, Typescript, ES6+, Expo, Apollo Client, GraphQL, Jest/Enzyme, React Navigation, NativeBase.io
