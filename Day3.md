1) Difference between Axios and fetch?

Ans===>  Axios

Axios is a Javascript library used to make HTTP requests from node.js or XMLHttpRequests from the browser and it supports the Promise API that is native to JS ES6. 

Axios is a stand-alone third party package that can be easily installed.

Axios performs automatic transforms of JSON data.

Axios allows cancelling request and request timeout.

Axios has the ability to intercept HTTP requests.

Axios has built-in support for download progress.



fetch

The Fetch API provides a fetch() method defined on the window object. It also provides a JavaScript interface for accessing and manipulating parts of the HTTP pipeline (requests and responses). 

Fetch is built into most modern browsers; no installation is required as such.

Fetch is a two-step process when handling JSON data- first, to make the actual request; second, to call the .json() method on the response.

Fetch, by default, doesn’t provide a way to intercept requests.

Fetch does not support upload progress.


//======================================================================================================================


2)What is UseState Hook ?(Implementation)

Ans===>The React useState Hook allows us to track state in a function component.State generally refers to data or properties that need to be tracking in an application.

https://codesandbox.io/s/nostalgic-bogdan-ph940u


//======================================================================================================================

3)What is useEffect Hook ?(Implementation)

Ans===>It allows us to implement all of the lifecycle hooks from within a single function API.

https://codesandbox.io/s/silent-hill-tm9n2h?file=/src/App.js