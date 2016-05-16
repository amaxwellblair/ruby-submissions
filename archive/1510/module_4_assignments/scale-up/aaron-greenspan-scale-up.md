# Scale Up Submission Form

## Basics

### Summarize the Work you Completed Over the Week

 Over this past week, we built a Phoenix/ReactJS app.  The app is itself fairly basic: It allows users to create accounts, and login with an encrypted password.  Once authorized, the user is presented with a counter from a database on the backend which increments itself using a parallel and supervised Phoenix process.  (This is pretty gnarly in its own right: aside from pure paralellism, if for whatever reason the counter incrementing fails -- e.g. because the db connection is severed for even half a second -- the supervisor restarts the incrementing as soon as it is able.) The user is then able to use a combination of AJAX and websockets to reset the server. 

### Link(s) to Your Work

 [The work](https://github.com/afg419/everybody_counts/pull/5)

### Talk about something that you didn't know about before this week.  

 Websockets, Phoenix, React, Parallelism... more or less everything.

### Link to blog post(s) submitted  

 [The link](https://medium.com/@afg419/computing-the-computational-complexity-of-merge-sort-with-ruby-2ed01af9e0ff#.nju6txod0)

### Discuss: your experience doing PR reviews and getting PR feedback  

 Super helpful getting feedback from Hector who was semi familiar with Elixir and my code base.  Overall for me and those giving me feedback, it was very easy to find superficial problems and fixes, but difficult to drop in and find serious things to comment on.  I almost think that if each of us were given a random day, and nothing to do on said day but comment on PRs, the reviews would be much more insightful and useful.

### Discuss: your experience doing daily stand ups

 It was fine!  I liked it.  I had fun.

### Please feel free to ask any other questions or make any other statements below!  

 hmmm.

-----

# Instructor Evaluation:

Points: (max 150)

### Blog Post (40 Points)  
  * 40: Developer has >= 2 blog posts documenting something they have worked on for their independent study or has one in depth blog post.

### Participation (50 points)
  * 50: Developer participated daily in stand ups with the group (remote or in person). Developer was able to speak to their work in stand ups in a way that was clear and informative. Developer was involved in pull request reviews.

### Risk Taking and Creativity (60 points)

Instructor/Developer will select one feature in the project to review for this section of the rubric.

  * 60: Developers pushed themselves and their team by taking risks which is demonstrated by a delivered feature. Developers explored concepts and technologies outside the scope of the curriculum.
