
1.What is Virtual DOM?

=> The virtual DOM is a representation of a DOM object. In React JS, every DOM 
element has a corresponding Virtual DOM Object. No doubt that the virtual DOM 
has the same properties as we have in the normal DOM object but unlike the DOM 
object where we can directly change what is on the screen, we cannot do that 
for the virtual DOM.
   It is clear that the performance provided by the Virtual DOM amazing. Not only that, below are some advantages of the Virtual DOM:
1.Speed and performance boost
2.Lightweight
3.It is simple and clear
4.Amazing diffing algorithm.


2.What is SPA?

=> SPA stands for Single Page Application. It is a very common way of 
programming websites these days. The idea is that the website loads all 
the HTML/JS the first time you visit. When you then navigate, the browser 
will only rerender the content without refreshing the website.
 This is used to make the user experience feel a lot smoother. When it’s a SPA or 
multi-page application when navigating between menus often because 
a multi-page application will reload, making the whole UI blink fast depending 
on the content. This is due to it refreshing the website. A SPA will instead 
feel smooth in the transaction as it simply shows other content without refreshing.

example for SPA : facebook, instagram, etc.,

3.Difference between Functional component and Class component?

=> Functional component:
*A functional component is just a plain JavaScript pure function that accepts props as an argument and returns a React element(JSX).
*There is no render method used in functional components.
*Functional component run from top to bottom and once the function is returned it cant be kept alive.
*Also known as Stateless components as they simply accept data and display them in some form, that they are mainly responsible for rendering UI.
*Hooks can be easily used in functional components to make them Stateful.
example: const [name,SetName]= React.useState(‘ ‘)

syntax: const function = () =>{
    return (
        <h1>It is a function component</h1>
    )
}

=>Class component:
*A class component requires you to extend from React. Component and create a render function which returns a React element.
*It must have the render() method returning JSX (which is syntactically similar to HTML).
*Class component is instantiated and different life cycle method is kept alive and being run and invoked depending on phase of class component.
*Also known as Stateful components because they implement logic and state.
*It requires different syntax inside a class component to implement hooks.

example: constructor(props) {

   super(props);

   this.state = {name: ‘ ‘}

}

syntax: class clscomp extends Componenet{
    render(){
        return(
            <h1>It is a class component</h1>
        )

    }
}

4.What does mean by state and its use in react?

=>State is a JavaScript object that stores component’s dynamic data and it enables
 a component to keep track of changes between renders. Because state is 
 dynamic, it is reserved only for interactivity so you don’t use it for 
 static React projects.
   Components defined as classes have some additional features. Local state is 
exactly that: a feature available only to classes. State can only be used within 
a class and usually the only place where you can assign this.state is the constructor.
Main points:
  1.State is managed within the component.
  2.Variables are declared in the function body.
  3.State can be changed.
  4.useState hook is used in functional component
  5.this.state is written in class component.


5.What is JSX and why do we use it instead of js?

=>JSX stands for JavaScript syntax extension. It is a JavaScript extension that 
allows us to describe React's object tree using a syntax that resembles that of 
an HTML template. It is just an XML-like extension that allows us to write JavaScript 
that looks like markup and have it returned from a component.

=>Use instead of js?
   JSX allows us to write HTML elements in JavaScript and place them in the 
DOM without any createElement() and/or appendChild() methods. JSX converts 
HTML tags into react elements. You are not required to use JSX, but JSX makes it 
easier to write React applications.

6.What is package.json?

=>The package. json file is the heart of any Node project. It records important 
metadata about a project which is required before publishing to NPM, and also defines 
functional attributes of a project that npm uses to install dependencies, 
run scripts, and identify the entry point to our package.
  It contains - All npm packages contain a file, usually in the project root, 
called package. json - this file holds various metadata relevant to the project. 
This file is used to give information to npm that allows it to identify the project 
as well as handle the project's dependencies.