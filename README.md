# The-Async-Force-Ep-4
An **async** exercise using **server side** XHR accessing the swapi API at https://swapi.co

##Exercise
*Remember to commit after each step*

1. Initialize the project as an node module with `npm init`
1. Make a new file and name it `app.js`
1. Install the request-promise npm nodule and its dependency with `npm install --save request request-promise`
1. Install the Bluebird Promise library with `npm install --save bluebird`
1. Look up documentation for the npm module named `request-promise` for usage.
1. Hit the SWAPI API at this endpoint: http://swapi.co/api/people/4
1. In the Object that gets returned from the API call, there should be an array of films which contain
   subsequent API endpoints to retrieve film data.  Get all the film names from the endpoints and replace all the
   URLs in the films array with the actual name of the corresponding film.
1. Log the results of your modified return Object to the terminal.
1. Your code should go in app.js
1. Use `nodemon` to re-execute your file everytime you make a change.

*Remember this is a server side exercise running entirely in the node environment*

##Hints
1. request-promise library repo https://github.com/request/request-promise
2. Information on promises http://www.mattgreer.org/articles/promises-in-wicked-detail/
3. Bluebird promise library docs http://bluebirdjs.com/docs/getting-started.html
