## Week Three - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week. 

Note: When you're done, submit a PR. 

1. At a high level, what is Node?

An open source server written in JavaScript.

2. What is Express? What is Express similar to in the Ruby world?

Express is a lightweight web framework similar to Sinatra.

3. How do we setup a route when creating an API with Node and Express? Please provide a code snippet.

```
app.get('<endpoint>', function(request, response) {
  <controller>.<controller function>(request, response)
})
```

4. What do we use Knex for?

We use Knex to interact with our database.

5. How **could** you organize your code to follow the MVC design pattern in your Quantified Self project?

Routes in `server.js`, controllers to handle the response, and models to get and manipulate data.

6. How do you execute raw SQL in node?

After setting `const database = require('knex')(configuration);`, `return database.raw(<SQL query>)`

7. What are some advantages to having your front end and back end code live in separate applications? What are some disadvantages?

Advantages: More organized application, single responsibility
Disadvantages: Room for error where the applications meet

#### Review  

8. Describe DNS.

Domain Name System - DNS is what allows us to type in things such as `www.google.com` as opposed to the IP address of their servers. 

9. What does writing clean code mean to you?

To me writing clean code means writing code that is reusable, testable, and DRY.

10. If you were building an application that models hotels, what classes would you need? What classes would be responsible for what functionality? Hint: think about what tables you would need in the database, how those records would relate to each other, and good OOP.

Hotel, room, guest, reservation, employee
