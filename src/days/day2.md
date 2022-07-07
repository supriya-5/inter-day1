
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

=>https://wvyz3b.csb.app/ (implemented in here)

4.How do you pass data from parent to child

=>by using props.

=>https://xf1kbf.csb.app/  (implementation part).

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



