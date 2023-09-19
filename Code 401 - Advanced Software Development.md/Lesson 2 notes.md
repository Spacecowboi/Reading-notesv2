## Introduction to NodeJS and Express

1. Explain middleware, answer as though I were a non-technical recruiter.

* I think a good way to explain this would be like you're at an airport. At the airport, there are several security checkpoints you have to get through in order to finally make it to your gate. Middleware is basically acting as the different "checkpoints" on your way to your gate. 

2. Express the most popular __ __ ____.

* Web Framework

3. Express is “unopinionated.” What does that mean?

* To keep it short, "unopinionated" in this context means the developer using express is free to do what they need to, generally how they want to.

4. What is a module and why is modularity useful to us as developers?

* A module is a piece of code that uses the single-responsibility principle to do one single thing. Modularity is useful for several reasons, but I think the most important is that it allows developers to be organized and keep related code together.


## What is NPM?

1. What version of npm are you running on your machine?

* 9.8.1

2. What command would you type to install a library/package called jshint into your node project?

* npm install jshint

## What is TDD?

1. Explain why tests are important. Please explain as though I were your non technical elder.

* Tests make sure that are applications and programs are working the way they are intended to work. The same way we have crash tests, math tests, food safety tests, our programming tests do the same thing.

2. What are three expected benefits of testing?

* Reductions in defect rates
* Reduction in effort in a projects final phases
* Improved design quality

3. Name at least 2 indidivudal pitfalls and at least 2 team pitfalls commonly encountered while writing tests.

- Individual

* writing tests that are too large or coarse-grained
* writing tests for trivial code

- Team 

* Poor maintenance of test suites
* Abandoned test suites. (usually never run)

## CI/CD

1. What are three benefits of Continuous Integration?

* If you are integrating changes earlier in the development process, it can help to identify and deal with bugs earlier rather than later.
* If you are working on a team and constantly pushing to a repository that others are working on mutliple times a day, it ensures everyone is on the same page.
* If you have a good practice for your integration, you can do more with your features and make them more accessible more frequently.

2. What is the difference between Continuous Delivery and Continuous Deployment?

* CI = This is basically a big safety net. You make changes that are built and tested, and then they get approved before moving to production.

* CD = This is like releasing a patch for a video game. The users still get to "play" the game, but the dev team is able to release "patches" that update the game with new features or remove existing ones, while the user still has access to the application.

3. Explain how Github fits into this process assuming the listener comes from a non-technical background.

* If you were working in a restaurant kitchen and everyone was working to build one dish that was going into the oven, GitHub is the oven. Everyone brings their "piece" of the dish to the oven (github) and the oven is where the meal is actually cooked so people can eat it. 