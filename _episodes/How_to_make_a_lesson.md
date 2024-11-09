---
title: How to make a Letsson
teaching: 30
exercises: 0
questions:
- How can I make a lesson like this from scratch?
objectives:
- Learn how to set up locally to build a lesson and to deploy it.
keypoints:
- If you can do basic markdown, you can do this. 
---


## here I describe how I built this lesson.  You can follow along. 

The Carpentries provide excellent instructions at: [https://carpentries.github.io/lesson-example/setup.html](https://carpentries.github.io/lesson-example/setup.html).  

> Note:  Carpentries has moved on to an 'R' based system which we are not using. We are stil using this older format.

- First you need to decide on a name for your new lesson.  Because github insists on using gh_pages for deployment, it is good to use your own github account for initial (and ongoing) development and pull over to /DUNE/ for the official version rather than using branches in the /DUNE/ github area.

- Then follow the instructions for setup on your local machine - in principle this is optional but in practice it is really helpful.  You are going to need ruby and pyYAML.  I used conda on a mac but they have instructions for Windows, Mac and UNIX. 

- Then go to the section [Creating a new lesson](https://carpentries.github.io/lesson-example/setup.html#creating-a-new-lesson) and import the repo [https://github.com/swcarpentry/styles/](https://github.com/swcarpentry/styles/)