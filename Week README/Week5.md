
## Monday

# Weekend challenge -> Group Review

- Is this a good tool? Should i be using it?

How secure is Bcrypt?
Is the library popular?
How often is it updated? Is it well maintained?
Dependencies -> and check documentation - is it good enough?

- Unique keys?
You can only have one primary key but you can have one unique key

- Primary key
Information must be unique to that table. Quick way of accessing particular row.

- Database: Anytime you make a change it saves in a database history.


- When to use instance variable and when class one? : instance for small parts of the code and classone when you call the whole class.

- ORM (Object-relational mapper)-> They provide set of class methods built in.

# Structure of the week

- Can you learn a new language and its patterns?

JavaScript
- Can you read and write JavaScript syntax?

- Can you understand the rules that govern the behaviour of the this keyword?

- Can you follow the flow of an Ajax request and response? * extra

- Can you follow the flow of control through code that uses callbacks? * extra

# Transferring your existing skills
Can you encapsulate behaviour in JavaScript?

Can you get visibility effectively in JavaScript?

Can you TDD in JavaScript?

Can you follow the flow of control over the whole web app cycle? e.g. the interface of a thermostat is displayed in HTML/CSS, the "increase temperature" button is clicked, a JavaScript click event fires, JavaScript code runs to handle the event, an Ajax request is made, a Sinatra controller POST action handler is run, a Thermostat Ruby model is updated, the new temperature is saved to a Postgres database, the new temperature is returned as JSON by the Ruby controller, JavaScript code runs to update the temperature in the web page.


JavaScript was very quickly written -> in 7 days! It was built to solve a specific problem to change things without making request to the server.


Before Javascript you always had to make a request. JavaScript is asynchronous language. Browser has events you can call(clicks, typing). We are going to run everything on the browser.

We will be working in ES5 -> slightly older version and less functionality

# Javascript

this - keyword refers to the object it belongs to.
It has different values depending on where it is used:

In a method, this refers to the owner object.
Alone, this refers to the global object.
In a function, this refers to the global object.
In a function, in strict mode, this is undefined.
In an event, this refers to the element that received the event.
