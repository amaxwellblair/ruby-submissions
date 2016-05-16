# RealTime Submission Form
[Project Spec](https://github.com/turingschool/curriculum/blob/master/source/projects/real_time.markdown)

------

# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/dastinnette/real-time)

### Link to the Deployed Application
[Your Application](http://just-like-your-opinion-man.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/dastinnette/real-time/commits/master)

### Provide a Screenshot of your Application
![This time it's real](http://i.imgur.com/WN3rrP8.png?1)

## Completion

### Were you able to complete functionality that fits both case studies?
Yes

### List any functionality from the case studies that is missing
No functionality missing

### Did you do anything outside the scope of the case studies?
Let's not get greedy

# Code Quality

### Link to a specific block of your code on Github that you are proud of
[Remove empty options](https://github.com/dastinnette/real-time/blob/ffd9429224cba04f2d81e38c8f30d0c00aed1e5e/server.js#L54-L57)
I had trouble displaying only the buttons that the admin entered choices into.
After experimenting with a few methods I found a way to make filter work and
only display the number of buttons in the poll view that the admin created
choices for.

### Link to a specific block of your code on Github that you feel not great about
[Server needs refactor](https://github.com/dastinnette/real-time/blob/ee3e619bb8903be458a82c1cc6a2fcb576866661/server.js#L100-L109)
I was able to extract a few methods out of the server.js file into their own
files in the lib folder but was not able to extract this and keep my tests
passing. With more time I would have made this work but kept the method in a
crowded server.js file to keep all tests passing.

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.
![Tests on tests](http://i.imgur.com/6ZnP0bS.png?1)

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

-----

### Please feel free to ask any other questions or make any other statements below!

-----

## Instructor Feedback

155/200

### Concept and Features

Does it have the expected features?

* 75 points - Met expectations as outlined by the user personas, the application is a solid first version. All planned features were delivered.

### Code Quality (JavaScript and/or Ruby)

* 20 points - Developer writes effective code, but does not breakout logical components. Application shows some effort to break logic into components, but the divisions are inconsistent or unclear. There are many large methods or functions and it is not clear to the evaluator what a given section of code does.

### Client-Side Application

* 25 points - Your application is thoughtfully put together with some duplication and no major bugs.

### Test-Driven Development

* 25 points - The code demonstrates high test coverage. It is tests at controller and unit levels. All controller/routes are tested. There are no failing tests.

### Interface

* 5 points - The application is pleasant, logical, and easy to use

### Workflow

* 5 points - The developer effectively uses Git branches and many small, atomic commits that document the evolution of their application.
