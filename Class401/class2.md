# Express, NPM, TDD, CI/CD

## An introduction to NodeJS and Express

* *Explain middleware, answer as though I were a non-technical recruiter.*

  * Middleware is a program that acts as a moderator for two programs talking to eachother. It basically will take the information from one program and check that its the correct info for the second program. If not, it will either correct it before passing it on or not since the second program wouldn't have any use for it.

* *Express the most popular __ __ ____.*

  * Express is the most popular Node web framework.

* *Express is “unopinionated.” What does that mean?*

  * Unopinionated means that it has fewer restrictions on the way things get done or what is used to get it done.

* *What is a module and why is modularity useful to us as developers?*

  * A module is a JS library/file that can be imported in.

## What is NPM?

* *What version of npm are you running on your machine?*

  * 19.8.1

* *What command would you type to install a library/package called ‘jshint’ into your node project?*

  * npm install -g jshint

## What is TDD?

* *Explain why tests are important. Please explain as though I were your non technical elder.*

  * Tests are important because it makes sure that the code that we have is processing data the correct way. If we feed it 2 and 3 and the function is suppose to add them together, we might want to maker sure that it spits out 5. Lets say the user enters -3 and .4, this might be something that we want to test to make sure that our code doesn't break. 

* *What are three expected benefits of testing*

  * Reducing the chance of errors from happening on the live site, by running tests before final production you reduce the chance of things breaking at final stages, it helps create better code.

* *Name at lest 2 individual pitfalls and at least 2 team pitfalls commonly encountered while writing tests.*

  * **Individual Pitfalls**
    * *forgetting to run tests frequently*
    * *writing too many tests at once*
    * *writing tests that are too large or coarse-grained*
   * **Team Pitfalls**
     * *Not everyone on the team using TDD*
      * *poor maintenance of the test suite*
      * *abandoned test suite*

## CI/CD

* *What are three benefits of Continuous Integration?*

  * Early Detection of errors
  * Faster Feedback Loops
  * Better Collaboration and Communication

* *What is the difference between Continuos Delivery and Continuous Deployment?*

  * The difference between the two is that Continuous Delivery's goal is to automate the process of building, testing and preparing software for release, whereas Continuous Deployment takes it one step further and add automatic deplyoment, without human intervention.

* *Explain how GitHub fits into this process assuming the listener comes from a non-technical background*

  * GitHub is how the code gets update to the live server. I think you can compare it to taking a picture on your phone and then posting it to instagram which automatically gets posted to facebook too. Github kind of acts like instagram, where it takes in the raw info, your code, runs tests and if those test pass, it sends it to facebook aka your deployed site.

I used chatGPT to help explain CD vs CD
