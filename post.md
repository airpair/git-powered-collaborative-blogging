

> This post is meant planned to be published March 2, with the official annoucement of AirPair's new authoring tools. Feedback most welcome.

## 1. `mkdir` cat-brace-pencil-mutant

### 1.1 `touch` TLDR;annoucement

Today I'm excited to annouce one of the coolest and innovative projects I've ever been involed with. Pretty much anything part git or Octocat is already going to be cool. If you've enjoyed reading the AirPair blog before now, it gives me great pleasure to let you know how much more awesome it's going to be from today onwards with the launch of our new Git Powered Collaborative Publishing workflow.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

I'll intertwine quite a few reasons why these tools are significant, while covering why we buitd this platform, how we put the it together and what types of things we hope to see. Before going into detail, perhaps much of the value of these tools can be summed up in this screenshot:

![Fork a post on AirPair](/static/img/pages/posts/fork-post-dymo.png)

With the power of forking, we can tackle some age old scenarios with far less friction.

- Annoyed with that typo? *Fixed*. 
- Code sample has a syntax error? *Fixed*.
- Sample no longer runs with new framework version? *Fixed*.
- Better way to do something? *Make it better*

### 1.2 `touch` README.md

** Table of contents **

If you haven't already read my mind (after all we built this to get one step closer to singularity), I want reaffirm that we believe this idea is significant, so in *Part 2* I will cover why developers need a git powered blogging system like this. In *Part 3* I will explain how the technicalities of how we put it together and what the flow looks like. In *Part 4* I'm going to leave off on the philosophical direction we're seeking, how you can be invovled in coming with us on the journey.

### 1.3 When Ideas Have Sex


### 1.3 What's in it for you?



#### For Readers

#### For Authors

### 1.4 Help us make this work

Were going to let the platform run for a couple of weeks for feedback before doing a marketing push in the first weke of March. Please help us at the beginning of march on social media.

```
git add .
git commit -m 'Intro to AirPairs new Developer Blogging Tools'
```

## Why build a Git Powerd Publising Workflow

To make it self sustainable
And to make content live more organically and age slower
People can help you maintain your post as versions change
But the principals remain valid
With a complete git backed history
And acknowledgement of contributors
It's a much deeper and social way to collaborate and share knowledge through this medium

####

 But to start, let me explain the white space in between the extreme long tail *Stackoverflow* sparked our imaginations, when everyone realized how neccessarily a consolidated resources of extreme long tail knowledge was. On the other end of the spectrum, PluralSight, 

Yes, people have published and translated books on github. Git is almost every developers favorite tool... but it was Github who took the tool and combined beautiful product and execeptional community building to make something, somewhere in-between technology and common conciousness, to bring about the next level of cognitive collaboration. Wow, the day I understood that you could work with someone without having met them, or even know thei name - I knew Github was my favorite startup.

## Our Publishing Flow

This is our first go at gluing the two systems together, so we might not have reached the optimal solution, and we'll probably learn a lot in the coming weeks.

### Draft => In Review => Published


## 1. The begining, middle, adorable abomonation & his baby

### Headings

## Use h2 for headings

- h1 is already reserved for your posts title, so don't use a single # heading

### h3 are good for sub-headings

Headings will appear automatically in your Table of contents. You'll be able to see them later when you click **PREVIEW**.

## Code blocks

Code blocks are the same as github flavored fenced code blocks. You can

```coffeescript
#Code blocks with language
```

```coffeescript,linenums=true
#Code blocks with language and linenums
() ->
  coolness = true
```

```javascript,linenums=true
//Code blocks for javascript
function() {
  var coolness = true
}
```

