# JavaScript Fetch, Promises and Web apis

JavaScript promises and the api at [Random Fox](https://randomfox.ca/floof) are used to display stunning pictures of beautiful foxes.

To get the pictures I use the fetch api with chaining   
  * ```fetch().then().then().then()```

  * fetch() returns a promise and each then() returns a new promise.   

> "Sometimes when an api is designed to use this kind of method chaining, there is just a single object, and each method of that object returns the object itself in order to facilitate chaining. That is not how promises work however. When we write a chain of .then() invocations, we are not registering multiple callbacks on a single Promise object. Instead, each invocation of the then() method returns a new Promise object. That new Promise object is not fulfilled until the function passed to then() is complete."  
--JavaScript the Definitive Guide, David Flanagan





