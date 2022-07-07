
1.What is the Difference between react and react native? Which one is library or framework?

=>react native:
React Native is an open-source JavaScript framework, designed for building apps on multiple platforms like iOS, Android, and also web applications, utilizing the very same code base. It is based on React, and it brings all its glory to mobile app development.

=>react:
React. js is an open-source JavaScript library that is used for building user interfaces specifically for single-page applications. It's used for handling the view layer for web and mobile apps. React also allows us to create reusable UI components.

2.What is the package name you are using for routing

=>The very first step to using React Router is to install the appropriate package. They are technically three different packages: React Router, React Router DOM, and React Router Native

*BrowserRouter: it keeps sync with UI and URL.
*Route: to render some UI when its path matches the current URL.
*Router:Allows you to handle routes in a wed app,using dynamic routering.

3.Routing Implementation

=>https://codesandbox.io/s/romantic-currying-wvyz3b

4.How do you pass data from parent to child

=>by using props.

=>https://codesandbox.io/s/xf1kbf?file=/src/App.js  (implementation part).

5.What is lazy loading in react ?

=>Lazy loading is a strategy to identify resources as non-blocking (non-critical) and load these only when needed. It's a way to shorten the length of the critical rendering path, which translates into reduced page load times.
Lazy loading is a great option for improving page performance and keeping visitors on your site. If you choose lazy loading, be sure to test your site with this new feature before launching it. Any bugs might prevent your hidden content from showing at all, and no content is worse than slow content.

6.Difference b/w Stateful and stateless Component

=>stateless:
If the behaviour is independent of its state then it can be a stateless component. You can use either a function or a class for creating stateless components. But unless we need to use a lifecycle hook in your components, we should go for function components. There are a lot of benefits if you decide to use function components here; they are easy to write, understand, and test, a little faster, and you can avoid the this keyword altogether.

=>stateful:
If the behaviour of a component is dependent on the state of the component then it can be termed as stateful component. These stateful components are always class components and have a state that gets initialized in the constructor.


7.How do you switch one component to another, Conditional Rendering

=>you can create distinct components that encapsulate behavior you need. Then, you can render only some of them, depending on the state of your application. Conditional rendering in React works the same way conditions work in JavaScript.

In React, we can create multiple components which encapsulate behavior that we need.
After that, we can render them depending on some conditions or the state of our 
application. In other words, based on one or several conditions, a component decides 
which elements it will return. In React, conditional rendering works the same way as 
the conditions work in JavaScript. We use JavaScript operators to create elements 
representing the current state, and then React Component update the UI to match them.
There is more than one way to do conditional rendering in React.
 They are given below.
  1.if
  2.ternary operator
  3.logical && operator
  4.switch case operator

