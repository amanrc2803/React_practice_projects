# React_practice_projects
Hans on project repo


Rendering with JSX Element 
   return <h1>Hello Avinash !</h1>;
   

Dom rendering without using JSX syntax 
    /return React.createElement("h1", null, "Hello Avinash !") */

Example of components creation in React 

    with the help of indext.js we can add more than one component at a time with the help of respective path.
    
    import React from 'react';
    import ReactDOM from 'react-dom';
   //import Dynamic_render from './Dynamic_render';
   //import Student from './Student';
   //import Card from './Card';
   import App from './App';

 and then we can render the dom compenent 
 
   
ReactDOM.render(
  <App/>,
  document.getElementById('root')
)
