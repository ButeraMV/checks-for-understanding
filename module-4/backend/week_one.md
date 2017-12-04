## Week One - Module 4 Recap

Fork this respository. Answer the questions to the best of your ability. Try to answer them with limited amount of external research. These questions cover the majority of what we've learned this week.

Note: When you're done, submit a PR.

1. What's the most useful thing you learned from completing the intermission week work?

  Learning how to write tests. I had some prior exposure to JavaScript but I had not done anything with testing.

2. What are some tools to help debug JavaScript code?

  Pry, browser console, `console.log()`

3. What are some tools you need in order to unit test your JavaScript?

  Mocha and Chai

4. What is the syntax for invoking a function? Give an example.

  `foo();`

5. What's `this` in JavaScript?

  `this` is a scoped instance of what it is called in.

6. What is Webpack and why is it useful?

  Webpack compiles our code into one file so that we don't need to link multiple script files to a page.

7. When/why do you want to use event delegation?

  When we want one event listener to fire off multiple different functions. Prevents us from writing more code than we need.

8. What's `npm` and what do we use it for?

  Node Package Manager, we use it to manage Node packages which are similar to Ruby gems.

#### Review  
9. What's the MVC design pattern? Describe each part of MVC.

  Model - handles logic and data manipulation
  View - what is displayed when a certain route is hit, html lives here
  Controller - manages the routing of the application

10. What are a few ways to optimize a Rails application?

  Better SQL/Active Record calls, Bullet for n+1, background workers, caching

11. What's a background worker? When would we want to use a background worker?

  A background worker is a separate app that handles things such as credit card validation. We would use on when we have a task that needs to happen many times and can slow down a user's experience in our app. They allow the application to continue what it was doing (since Ruby is single threaded) and the task will be taken care of somewhere else.

