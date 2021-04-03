---
date: 2021-04-03T09:03:37Z
hero_image: "/content/images/sharon-mccutcheon-Th_WZMUPnO4-unsplash.jpg"
tags: []
author: ''
title: Project planning and roadmaps

---
# Introduction

Currently, I'm doing a project in which I've "accidentally" been tasked with planning out the features. I find this quite hard to do and I'm not sure what the right way is if there is such a thing at all. It seems like a good topic to think about, so let's explore it a bit out loud.

When someone pitches a job or idea to you they often ask you to quote stuff. When it's a bit larger than the average marketing site you might just decide to write something or plan it a bit more rigorously. So you start up a Trello or Notion template, a more user-focused productboard, or even try to do it the "right" way by starting up a full-blown Jira board. You plan out the issues and tasks you need to do, which often ends up being a really long and messy list of entities of different sizes. When you notice this, you start asking yourself the question: Shall I write down more organizationally oriented features, issues, or tasks that collaborators understand? Or do I take a more technical perspective and write down views, components, interfaces, actions, down to the individual functions so that people understand the technological layers and concerns a bit better? Soon you realize this is a near-impossible feat, and decide to just wing it. Writing down everything and structuring it in a proper way takes more time than actually building it and see where that takes you. Especially when working alone you hit the next thing on the list in a very intuitive way without planning at all. You just need to put the work in, and at a certain point, the work is done.  So when writing a quote you put your finger in the air, guess some random number within a certain range, and jot it down. You've got wonderful time logging software, so you know exactly how little you earned later on.

On the other hand, you have your education in information science, the stuff you read, and your previous experience. You often hear about the big methodologies for organizing projects, like the dichotomy between waterfall and agile methodologies. The "big design up front" waterfall methodology always yields unhappiness because it tries to control the unknown. Yet you know that the agile methodology always ends up with the wonderful anecdote "let's design in code", which is short for let the developer spend time on product management and UI / UX design in a tool that is incredibly inefficient for those jobs due to its high specificity. You also get confronted with the large organizational gap between business needs and technological implementation. Both large methodologies seem terrible in their extremes. Yet the concepts you've learned gnaw at you and you don't want to waste time building something nobody will appreciate. You need to know who your user is, what they want to do and how they achieve value by those things. If you write well, you even capture some context, like where or when they want to do those things. The various formats of a user story seem like a nice template to capture your "features".  Yet you also know that deploying a format like this, or a theory in general, is the perfect way to make a messy situation even worse.

So you are locked between the academic "it depends on the context" and the practical need and issues of planning. So how to break this up a bit better?

## What and how am I planning?

![](/content/images/microsoftteams-image.png)

So yesterday night I was back into the mess of planning with way too many entities available. This time I was using Productboard to produce a set of features for the project I was working on and I was asked to produce a roadmap. Yet I after a few hours of playing around I wasn't able to make something good, which was confirmed by some feedback on what I had been doing. So in the evening I started to abstract from the things I had been doing during the day and created this whiteboard. It shows three levels, the organization level with stakeholders and processes and the system level with front-end and back-end (which ended up being largely the same).  

![](/content/images/img_0975.jpeg)

I was messing around with multiple entities:

* **Requirements:** Quite general things like security or usability 
* **Processes:** content strategy, design workflows, CI/CD, technology and user monitoring & analytics, or even marketing. 
* **Features:** Things that the user would really like to have or we would like to build for this or that reason. 
* **Issues:** Things that a causing us or users problems, like bugs and reported UI / UX problems, often things that look small but might be deceptively complicated. 
* **Tasks or sub-features:** Smaller entities, to break up the complexity of the larger entities.

I also wanted to apply them against time, so I started using: 

* **Timeframes:** Basically a start and end date for an entity
* **Releases:** Groupings of entities within a timeframe, to create packages of features

Note that this was already an improvement, I tried to do this a few times before, and sometimes I even went down to a technological level in planning by using things like:

* **Applications or services:** The largest entities within a system
* **Components, modules, or views:** Large entities by which you break up a system
* **Interfaces:** The boundaries between components
* **Actions or events:** The things that can happen within the system
* **Functions or objects:** Even smaller bit and pieces of the application

Apparently, I'm still dealing with the question of which abstraction level I should use to think about these things. Each of these entities describes important things, yet when to use which is a thing of experience. I was bringing my own knowledge as a developer and I was bringing some knowledge as an information scientist. I was also engaging with the possibilities and constraints that Productboard was pushing onto me. But all of these different views actually didn't make things easier, it actually made things complicated. Perhaps because I don't understand the boundaries between all of these concepts all that well or perhaps because this is always very hard to do well. In truth, it doesn't matter what my level of knowledge is, the job still needs to be done else we're back to"let's see what happens" or "let's go plan & design in code". That kind of defeat cannot be tolerated.

# What to do about it?

So the question arises, what to do about it? How to make this productive 