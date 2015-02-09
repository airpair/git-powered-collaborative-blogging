--

> *** Author's Request: This post is planned to be published March 2nd, with the official annoucement of our new Github powered authoring tools. We're going to let the new features run for a couple of weeks for feedback. We'd love to hear what you think and we'd also love your help spreading the word on social media first week of March, and please not before then :). Feel free to fork this post and make suggestions via Pull Request too.***

## 1. `mkdir` cat-brace-pencil-mutant

TODO *Insert funny pic of octocat with airpair brace and pencil*

TODO add CTA to subscribe to the AirPair Content Mailing List

### 1.1 `touch` TLDR;annoucement

Today I'm excited to annouce one of the coolest and innovative projects I've ever been involed with. Pretty much anything part git or Octocat is already going to be cool. But if you've enjoyed the AirPair blog before already, it gives me great pleasure to let you know how much more awesome it's going to get. From today onwards you're invited both as author or reader to contribute to our blog with our new *Github Powered Collaborative Publishing Workflow*.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

I'll intertwine many reasons why these tools are significant, while covering why we built them, how we put the the flow together and what types of things we hope to see. Before diving into detail, perhaps much of the value can be summed up in this screenshot and a few uses cases:

![Fork a post on AirPair](/static/img/pages/posts/fork-post-dymo.png)

- Annoyed with that typo? ***Fork and Fix***. 
- Code sample has a syntax error? ***Fork and Fix***. 
- Sample no longer runs with new framework version? ***Fork and maintian***. 
- Better way to do something? ***Fork and suggest enhancement***. 

### 1.2 `touch` README.md

** In this post (Table of contents) **

I'm going to finish of **Section 1** with a few main points in case you want to come back to read the read of the post later. If you haven't already read my mind (after all, we built this to get one step closer to singularity), in **Section 2** I'm going to cover when ideas have sex, why developers need a git powered blogging system and drive home why we think this is a big deal. In *Section 3* I will explain how the technicalities of how we put it together and what the flow looks like. In **Section 4** I'm going to round things off on the philosophical direction we're seeking, cover how you can be invovled in coming with us on the journey. Finally **Section 5** will summarise what's been said in a cohesive conclusion.

### 1.3 `touch` What's in it for you?

Here's a list of things we think are bleeding edge wins. Read this whole post to explore how and why. They are merely listed in this section.

#### For Readers

- More comprehensive and up to date content than ever before.
- The ability to contribute even if only being an expert in on a small nugget of subject matter.
- Lower bar to entry to interact with thought leaders who author.
- Clear signals that a post is worth reading by who it has been endorsed by.

#### For Authors

- Expontential help from readers taking your work from 9/10 to 10/10 quality.
- An *MVP* like forum to introduce new ideas and attract peers that can help evolve them before released to the public.
- Exposure to significantly more readers than publishing on your own blog.
- Recognition and personal branding for great work, even when no one has heard of your before.

### 1.4 `git commit "Intro to AirPairs new Developer Blogging Tools" -m` :

I hope you're excited as we are and you find time to read the rest of this post now, or another time. You can use AirPair's bookmark feature to collect content on AirPair that you'd like to revisit.

We're excited to make this work, but community is only part technology. That's one of the things we care about at AirPair, all the nodes and connections that make up real thriving community. We hope that this becomes another way the developer world makes not only the evolution of knowledge, but experiences each other on a personal level for plain old simple human connection. Now's the perfect time to become part of this, by help us get things off to a great start by sharing on social media (assuming you're reading this from March 2 onwards!).

## 2. `mkdir` why-build-a-git-powered-publishing ?

### 2.1 `touch` When Ideas Have Sex

#### 2.1.1 Collaboration as evolution

One of the pillars that inspired me to take the plunge and start AirPair, was that it embodied many of the ideas presented in my favorite TED Talk of all time [When ideas have sex by Matt Ridley](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en). The overarching themes that inspire me are that the idea that the more we interact, the more we converse and share knowledge the more our ideas combine and mutate to form knowlege evolving at an accelerating pace.

#### 2.1.2 Developer ideas you've already seen having sex 

If you use GitHub, you'll see what a company can enable, by reducing the friction for a community to interact between itslef. GitHub has always been my favorite StartUp since I moved to San Francisco, because it empowered people who had never met, or even knew each others name to collaborate and improve work. There's no doubt that there are more programmers, writing better software because of what they built and as a result all the code bases that became visible and mutatations that resulted.

#### 2.1.3 Sexy ideas on AirPair

You've seen what a great job GitHub did around 'Social Coding'

We'd like a shot from you, to champion the idea of 'Social Code Blogging'

In this regard, AirPair's mission is like Github's and though we're known for our primary busines model or connecting people through the medium of one-on-one remote pair programming, it is only one expression of what we're trying to do. Our workshops section which hasn't got much love recently is another which one day we'd like to rekindle. But let's focus on today's events and what we predict will happen if this works.

As a reader you will get smarter, as you will be exposed to better content improved through crowdsourced spelling and grammer improvements, pre-vetted ideas and statements, and lower bar to partcipate and contribute with resulting self improvement by engaging and only bits and pieces of a collaboratively created post that belong mostly to an author and also partially to it's contributors. If you don't want anyone to make suggestions on what you write, this might not be for you.

As an author you will make better work and be help, plus challenged to improve what you present. If you're so interested in a topic that you are going to spend hours or days sharing it, it's a no brainer to be given people passionate about what you've got to say that you don't have to find by maintaining a consistant blog that already made you famous. Ods are, if you post something on your own blog, many people will spot and think the same improvements, but you never become a aware of many of them because it's too hard for them to get what they see in their head onto your published piece. We hope we can help you engage that percentage of your readers.
 
### 2.2 `touch` Things we needed to solve for ourselves

### 2.3.1 `touch` Making our content effort self sustainable

Not all of this idead around this release formed at once. It is itself an evolution of sexy experiences across our team, experts and previous authors. Some parts are for the glory of Mankind's next step onto the cyber moon. Others are just marketing problems we wanted to solve, which are probably happening all over the internet. You might want to consider hosting your technical content on AirPair if you want to take advantage of our solution, or in the next section we'll tell you how we did it, so feel free to take our technical approach and mutate it. How could would the web be if it was all forkable.

#### 2.2.1 Reducing content half life

As an author who devotes personal blood sweat and tears, or a party that comissions content, you want to see what you make stay as fresh and relevant as you can.

Software might be the most promiscuous discipline of our time. Ideas converge so quickly that without a special career history, if you you've been out of the game for 18 months, you're possibly not hirable anymore. Ods are the framework that you mastered has a new version that could have been named something totally new, or it's no longer cool to use.

Thus, publishing technical content has less return than other subject matter. I wonder if this explains why there is no universal technical blogging platform, when there is a universal technical Q & A platform - StackOverflow - which supplies by far the majority of long tail knowledge for the developer world. Is it the way they captured community and empowered it to socially collaborate? I'm suprised this didn't happen in a big way yet anywhere for the blog post / tutorial format. It seems obvious, so I'm glad we're here having a crack.

##### 

When a developer writes an amazing piece, often the specific, syntax, interfaces will be out of date well before the principals become irrelevant.

A git powered platform will enable content to morph with external shifts in framework releases, vulnerability discoveries and other evolutions of software thought.

Who knows, one day we might go as far as implement some sort of tagging and branching so that you can even view releases of a post if you have to go back and do some maintenance. Until then, you could follow all the commit logs and even discussions on pull requests submitted to each post on AirPair to get what communal interaction lead to something being preseted how it was, just like any other opensource software made by collaborating developers.

### 2.3.1 `touch` Motivating more authors and content

At the end of the day, if an author shares something with the public, the ultimate goal is having it be read for (a) reconition, (b) interaction, (c) improvement (d) properity. We got off to an awesome start last year, generating significant traffic by seeding out posts section through paid well contributions and excellent covereage. The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficed post so far has been read more than 200,000 times and 24 hour record is 35,000 vistors.

We believe the ideas presented here around 'Social Code Blogging' will be a way to make last years success for authors the starter, before mains.

#### Recursively growing audience

The more authors publishing, the more readers visiting. So our strategy is to make this the best place for authors to write. We hope these new collaborative social features and our 100k writing competition starting first week of Feb are a good start. Let us know if there is anything else we can do to help make AirPair your go to scratch pad for emerging ideas in your head.

#### Self improvement

##### Improving knowledge on your subject matter

Sharing knowledge on AirPair doesn't mean only teacher transfers knowledge to student. Philosphically we are trying to address student to teacher and teacher to teacher and teachers to self. When you write a post, people less knowlegable than you will still help you re-think your first draft sometimes by just letting you know they don't get it. You'll be exposed to others who have strong opinions about your claims and solidify your argument to pass their high standards and of course as soon as you begin putting pencil to paper you are already re-arranging and improving knowledge structures around what you are expressing.

Without too much detail on the how, we'll eventually launch features to help you automatically enagage the right level of reviewers all the way up to industry thought leaders that you wished would comment on your creations as your post becomes positively reinforced by community reviewers.

##### Becoming better at written expression

There's going to be a portion of readers who are more able to help you express yourself better than improve subject knowledge. If you've always wanted to improve at writing, this might be new and powerful tool. I know I'm excited for this.

##### Form new friends and sub-communities around your interests

With your contributors acknowledged and listed on your published work, we hope over time to foster recuring bonds. People you become familiar with for having your back, also happy to help with a tweet or share to let the world know your shared work is ready. Many you might realize that you have their back and enjoy bouncing their ideas back when it's their turn.

This already happens over the internet and twitter for veteran personalities and bloggers. We think, we can lower the bar for the masses.

### 2.2 `touch` making-our-content-plaform-self-sustainable

 But to start, let me explain the white space in between the extreme long tail *Stackoverflow* sparked our imaginations, when everyone realized how neccessarily a consolidated resources of extreme long tail knowledge was. On the other end of the spectrum, PluralSight, 

Yes, people have published and translated books on github. Git is almost every developers favorite tool... but it was Github who took the tool and combined beautiful product and execeptional community building to make something, somewhere in-between technology and common conciousness, to bring about the next level of cognitive collaboration. Wow, the day I understood that you could work with someone without having met them, or even know thei name - I knew Github was my favorite startup.

## How AirPair's Publishing Tools Were Built

### Our Publishing Flow

This is our first go at gluing the two systems together, so we might not have reached the optimal solution, and we'll probably learn a lot in the coming weeks.

### Draft => In Review => Published


```javascript,linenums=true
//Code blocks for javascript
function() {
  var coolness = true
}
```

## 4. `mkdir` where-to-from-here ?

### Building AirPair's Blogging Community

### Partnering with Technology and API providers

## 5. `mkdir` conclusion

We hope this project is as impactful and we think can be and that news of these tools travel through the developer world. At AirPair we wake each day focused on how we can make a thriving company around the core values of enabling knowledge to transfer more easily from one mind to the next. We're looking for amazing, top notch engineers who want to build and market new ideas like this. Drop us a line if you'd like to work on things like this.
