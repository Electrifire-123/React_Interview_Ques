1. Differentiate between stateful and stateless components.
Ans:- 

2. What is React?\ What are its features?\
Ans:-React was created by Jordane Walke, a software engineer at facebook in the year 2011 and it was deployed first at the facebook newsfeed and later it was used in facebook and instagram. React is a Open source front end JS library. It follows the component based approach for building reusable UI components specially for single page application and it is used for developing interactive view layer of web and mobile application.

    Features 
    1. Virtual DOM
    2. One way Data Binding
    3. Reusable Component
    4. JSX (JavaScript Syntax Extension)
    5. Performance

3. Explain Virtual DOM?\
Ans:- DOM is a document object model, created by converting HTML CSS and JS Real DOM, which is an object which gets created whenever any React application gets loaded on the screen for the first time., whenever React components gets mounted on the screen for the first time. Now when any user makes any changes on the screen like button click because of which the state variable will get updated so in this case the changes will not directly go to Real DOM , instead in react we have concept known Virtual DOM. So we are having two virtual doms, one virtual dom gets created at the time of mounting of react component so it is a copy of your real dom. Another virtual dom is the dom which contains the new changes, updated state variables values. Now these two virtual doms will get compared with each other and will check for the new changes. this complete procedure is known as diffing algorithm. Now the new changes will be updated in your Real dom. this procedure is known as Recoinciliation.

4. LIbray or framework?\
Ans : - Library is a set of reusable functions used by computer programme and framework is a piece of code that dictates the architecture of a project , code calls the library but in framework , framework calls the code. in libray we can control the data flow by methods but in framework we dont have any control of the data flow framework decides how the dat awill flow that is nothing but frameworks callls the code. and in perfornmance wise react is having higher performance over angular and veu and community support and also react is having the easy learning curve and react is having SPA(Single page application) .

5. Class components VS Functional Components?\
Ans:-       i. Class Component uses the Lifecycle methods where as in functional component have HOOKs
             ii. Functional component are also called stateless component while class component is called statefull component and there is no render function while in functional there is return  
             iii. functional component accepts props as argument but props and state can be accepted in class components
             iv. Functinal Componenrs are easty to read as they have less code but the class components have complex code structure and hard to write.
             v. In class component we uses the "this " keyword but in functional we dont need the keyword.


6.  Differentiate between stateful and stateless components.
Ans:-
Ans :- Stateless component does not hold or manage state While statefu;ll component can hold or manage state, Stateless component are easy to understand but the statefull component it is complex as compared to the stateless components. Stateless component does not work with react lifecycles but whreas statefull work with lifecycle methods. Stateless can not be reused while can be used in case of statefull component.Stateless compnent is also known as functional component. Statefull is known as class component

7. What are the different phases of React components lifecycle?\
Ans:- In ReactJS, every component creation process involves various lifecycle methods. These lifecycle methods are termed as component's lifecycle. These lifecycle methods are not very complicated and called at various points during a component's life. The lifecycle of the component is divided into four phases. They are:
         1.	Initial Phase
         2.	Mounting Phase
         3.	Updating Phase
         4.	Unmounting Phase
         Each phase contains some lifecycle methods that are specific to the particular phase


8. Differentiate between states and props?\
Ans:-   i. State changes can be asynchronous
        ii. Props can be readOnly
        iii. Props can be accessed by child components
        iv. states cant be accessed by child components
        v. Props are used to communicate between components 
        vi. state can be used to change render dynamic changes within the compontent
        vii. Propst are Immutabe
        viii. Props are external and controls by whatever render the component
        ix. state is internal and controls by react components itself
    
9. Explain props drilling concept and state uplifting?\
Ans:- 1. Props Drilling: 
            i. It is a basically a suitable in the same data is been sent to almost every level due to the requirement in the final level
            ii. when we have to share the same data across multiple child component then define the state in the parent component or common ancestor.
            iii. Every components in react has its own state because of these sometime data can be reabundant and in consistant so by lifting up the state of the parent component as a single source of the truth and pass the data of the children in its parent.
        
    
10. What do you know about controlled and uncontrolled components?\
Ans :-  In the react component data is control by the parent component 
        In the uncontrolled component data is controlled by the dom itself.
        Control components allows the validation control
        whereas uncontrolled does not allows the validation
        In control component it has better control over the forms and data 
        In uncontrolled component it gives limited control over the forms and data.

11. What is React Router?\
    Ans:-   It is a standard library for routing in react it enables the navigation among the views of various pages in react application, and it allows to change the browser URL 
            React Router plays an important role in SPA to load multiple views.

