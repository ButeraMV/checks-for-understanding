## Week Two - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. What's one difference between ES5 and ES6?

Function syntax

2. What's the difference between asynchronous and synchronous JavaScript? 

Synchronous means that the code cannot work on the next part of something until it finishes the first. Async is when AJAX is being used, and it allows us to make calls and do other things with our code at the same time.

3. What are the four pillars of Object Oriented programming?

Encapsulation, Abstraction, Inheritance, Polymorphism

4. What are some tools available in JavaScript to help you write object oriented code?

Class constructors

5. What are some key concepts to be aware of when refactoring your JavaScript?

Unused code, DRY, SRP

6. What's a callback function and what are some reasons when we use/need callback functions?

A function that is passed as an arguement to another function. We use them a lot for things like `.on('click', function(){...}`

7. What are the different scopes of variables in Javascript? When would you want to define global variables?

Local and Global. You would define global variables when you need to access them throughout your code, not just in a block.

8. What's the difference between `==` and `===` in JavaScript?

`==` will do type conversion (ex: string to integer) while `===` will not (strict equal)

9. Why do front end frameworks exist?

To allow us to do things easier and faster. Frameworks are made because people don't want to write the same code over and over again, and the framework gives us a way of doing what we want to do.

#### Review  

10. Why do people say "HTTP is stateless"?

Because it does not hold state. Can only pass information over HTTP and not something specific about a model for example.

11. Describe a RESTful API.

A RESTful API is an API that uses the standard HTTP verbs (GET, POST, PUT, DELETE)

12. What are some main characteristics of a team following an agile workflow?

Scrums, TDD, features being pushed out rather than one complete project.

13. What are some advantages **and** disadvantages to using OAuth to authenticate a user?

Advantages: Don't have to roll own authentication, trusted third party can instill confidence, secure, simple to set up
Disadvantages: User traffic is exposed to the third party, requires user to have a login for something other than your site (ex: sites that have a facebook login I can't get into because I don't have a facebook)

