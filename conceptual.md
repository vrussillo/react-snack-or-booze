### Conceptual Exercise

Answer the following questions below:

- What is the purpose of the React Router?
**It allows us to change the URL without individual page loading. We can maintain a single page app but have additional URL's to access or bookmark for example.**
- What is a single page application?
**It's a way of having a single URL that never refreshes but the components will.**
- What are some differences between client side and server side routing?
**We can load URL's with different information that doesn't have to communicate with the server**
- What are two ways of handling redirects with React Router? When would you use each?
**We can use the redirect component in React or the useHistory Redirect.**
- What are two different ways to handle page-not-found user experiences using React Router? 
**a Redirect component with a <NotFound /> catchall component with a Switch or a .push method on the history object**
- How do you grab URL parameters from within a component using React Router?
**useParams**
- What is context in React? When would you use it?
**When a nested component can access variables without having to decalre through every single nested component**
- Describe some differences between class-based components and function
  components in React.
  **A functional component is just a plain JavaScript function that accepts props as an argument and returns a React element. A class component requires you to extend from React.**
- What are some of the problems that hooks were designed to solve?
**Before hooks React didn’t have a basic way of extracting and sharing logic**