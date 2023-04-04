# Express REST API

## Review: ES6 Classes

* *Classes are a template for creating ____.*
  * Objects
* *Can a class declaration be hoisted?*
  * No, they have temporal deadzone restrictions
* *How would you describe a constructor and contextual “this” to a non-technical friend?*
  * A constructor is a automated process that creates objects. this. is a way of accessing the object that is currently being created.

## Using Express Routing

* *Within Express, what does routing refer to?*
  * Routing refers to how an application’s endpoints (URIs) respond to client requests.
* *What is the difference between a route path and a route method?*
  * A route method is derived from one of the HTTP methods, and is attached to an instance of the express class. || Route paths, in combination with a request method, define the endpoints at which requests can be made. Route paths can be strings, string patterns, or regular expressions.
* *When is it appropriate to add next as a parameter to a route handler and what must you do if next has been passed to your middleware as a parameter?*
  * Its appropriate if you are using a middleware and you are passing in request and response. If you are using it in a middleware, you must invoke next or your middleware won't go to the next thing.

## Express Routing

* *What is an Express Router?*
  * It is a mini express application without all the bells and whistles of an express application, just the routing stuff.
* *By what means do we initialize express.Router() in an express server?*
  * var router = express.Router();
* *What do we use route middleware for?*
  * Route middleware processes requests and validates parameters
