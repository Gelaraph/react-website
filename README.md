1. List five significant features of React.

   - Components Support
     ReactJS is a perfect combination of JavaScript and HTML tags. The usage of the HTML tags and JS codes, make it easy to deal with a vast set of data containing the document object model. During this time, ReactJS works as a mediator which represents the DOM and assists to decide which component needs changes to get the exact results.

   - SEO-friendly: React JS was introduced after immense research and improvements by Facebook. Naturally, it stands out from the crowd and allows developers to build amazing, SEO-friendly user interfaces across browsers and engines.

   - Proficient Data Binding: ReactJS trails one-way data binding. This means that absolutely anyone can track all the changes made to any particular segment of the data. This is a symbol of its simplicity.

   - Virtual DOM: React uses a Virtual DOM to update the UI efficiently. The Virtual DOM is a lightweight representation of the actual DOM, and React uses it to track changes and update only the parts of the UI that need to be updated, rather than re-rendering the entire UI.

   - Unidirectional Data Flow: React follows a unidirectional data flow, which means that data flows in a single direction, from parent components to child components. This helps to prevent unexpected changes to the UI, as data is always passed down from the parent component, rather than being updated directly by child components.

2. List five major advantages of React

   - Makes JavaScript coding easier
   - Excellent cross-platform support
   - Handles dependencies
   - Provides amazing developer tools
   - Easy to adopt

3. What is the name of the Software Engineer that created React? Also, which company owns React?

   - React was created by Jordan Walke, a software engineer at Facebook, in 2011 and it was later released as an open-source project in 2013. Presently, React is owned and maintained by Facebook.

4. What are the notable differences between HTML & JSX? Give at least 3 of them

   - In HTML, multiple elements can be returned.
     For example:

     ```
         <ul>
             <li>unordered list
                 <ol>
                     <li>ordered list</li>
                     <li>ordered list</li>
                     <li>ordered list</li>
                 </ol>
             </li>
             <li>unordered list</li>
             <li>unordered list</li>
         </ul>
     ```

   - while nested JSX must return one element, which we’ll call a parent element that wraps all other levels of nested elements:

```
  <div>
      <p>pink</p>
      <p>yellow</p>
      <p>green</p>
  </div>
```

Without the wrapper element, JSX won’t transpile. In React, we can render JSX directly into HTML DOM using React rendering API, aka ReactDOM. The formula for rendering React elements seems like this:
ReactDOM.render(componentToRender, targetNode)
ReactDOM.render() must be called after the JSX elements declarations.

- It is not necessary to use camelCase for attributes, ids and event references. Its totally your call to use camelCase, lowercase or hyphens for naming them.
  All HTML attributes and event references in JSX become camelCase, this way, onclick event becomes onClick and onchange — onChange.

- In HTML almost all tags have an opening and a closing tag except probably a few like <br/>
  While in JSX, however, any element can be written as a self-closing tag, for example: <div/>
  Example:

```
const string = <img src={user.avatarUrl}  />;

```

5. Why can’t browsers read JSX?
   - Browsers cannot read JSX directly because it is not a valid JavaScript syntax. JSX is a syntax extension for JavaScript that allows developers to write HTML-like code within JavaScript.
