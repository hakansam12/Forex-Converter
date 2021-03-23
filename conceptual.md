### Conceptual Exercise

Answer the following questions below:

- What are important differences between Python and JavaScript?
JavaScript is a scripting language used to create and control dynamic website content.
Python is an interpreted, object-oriented, high-level programming language with dynamic semantics.


- Given a dictionary like ``{"a": 1, "b": 2}``: , list two ways you
  can try to get a missing key (like "c") *without* your programming
  crashing.
1) setdefault(key, def_value)
2) get(key,def_val)

if the key is missing, then these two methods will create the key and add it to the dictionary.

- What is a unit test?
A unit test is a way of testing a unit - the smallest piece of code that can be logically isolated in a system. In most programming languages, that is a function, a subroutine, a method or property.
- What is an integration test?
Integration tests determine if independently developed units of software work correctly when they are connected to each other.

- What is the role of web application framework, like Flask?
A framework "is a code library that makes a developer's life easier when building reliable, scalable, and maintainable web applications" by providing reusable code or extensions for common operations.
- You can pass information to Flask either as a parameter in a route URL
  (like '/foods/pretzel') or using a URL query param (like
  'foods?type=pretzel'). How might you choose which one is a better fit
  for an application?
if a web application requires a lot of features, there must be subunits so that users can interact with the it.
In order to provide the data to a client, you must use a URL query params, otherwise you can add simple parameters.

- How do you collect data from a URL placeholder parameter using Flask?
you can use requests.get('name_of_data')
- How do you collect data from the query string using Flask?
 request.args: the key/value pairs in the URL query string
- What is a cookie and what kinds of things are they commonly used for?
a cookie can be used to save data about the client and added to the URLs to provide more information
- What is the session object in Flask?
In the flask, a session object is used to track the session data which is a dictionary object that contains a key-value pair of the session variables and their associated values. The following syntax is used to set the session variable to a specific value on the server.
- What does Flask's `jsonify()` do?
it will turn a data set into a dict. or a object
