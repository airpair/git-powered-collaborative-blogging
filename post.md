<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1 An AirPair GitHub Baby

*TODO: insert fun cat writing illustration*

### 1.1 TLDR; Social Authoring announcement

Today I'm excited to announce one of the more innovative projects I've been involved with. Pretty much anything part Git, or Octocat related is going to be cool. If you've already enjoyed AirPair's posts section, it gives me great pleasure knowing that our community content is about to get way more awesome. From today, you are invited to join our ***Social Authoring*** experiment as an author wanting to publish your own posts or reader interested in contributing to posts by others. Using our new *GitHub Powered Publishing Workflow*, authors and readers can work together using **Forks and Pull Requests** to produce better technical writing than ever before.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

In this post, I'll intertwine many cool opportunities that make our new authoring setup significant, while covering why we integrated GitHub into our posts section and how we put the the workflow together. We'll end leading into our ***$100,000 Writing Competition***, but before deep diving into details, here's a screenshot and some use cases to get you thinking:

![Fork a post on AirPair](//airpair.github.io/img/2015/01/fork-examples.png)

Here are some outcomes we think readers will love:  

- More proofed, comprehensive and up to date content than ever before
- Clear quality signals from our review system that a post is worth reading
- **Ability to contribute** small nuggets, without a comprehensive understanding required to author a whole post

Here are some pros we think authors will love:  

- Exposure to more readers and feedback than publishing elsewhere
- Crowdsourced help improving your posts
- A forum to bounce and evolve whacky ideas before they become public
- Instant exposure for great work, without previously building traffic or a following

### 1.2 Getting your hands dirty

- **[Starting a post](/posts/new)** is a piece of cake. 
- Forking is as easy as hitting the orange *Fork* button in the right rail.
- Review posts with the review widget at the bottom of each post
- Browse [Posts in review](/posts/in-community-review) to give feedback and help QA before publishing.

<!-- *TODO mention sharing and put share widget here* -->

** Bookmark this post **

We hope you like what you've seen so far and are eager to read on. You might consider using AirPair's bookmark feature for an easier way to return here later. 

## 2 Why Build Git Powered Publishing?

> "*How cool would it be if every page on the web were forkable?"*

This section covers a gamut of different forces that led us to combine the GitHub API with our existing authoring tools. Some of our motivations came from a sense that this could be groundbreaking. Indeed even evolutionary... Other guiding influences were simply marketing problems we needed to solve. Challenges that are probably relevant to everyone publishing on the web. Mostly though, we've had a great time working with our authors who inspired more than a million readers to come to AirPair in the last few months. Our main impetus was to make the experience of Authoring on AirPair easier and more impactful. To quote a friend who's tweet flew by mid-way through writing this post:

![Make things easier](//airpair.github.io/img/2015/01/making-things-easier.png)

### 2.1 When (Developer) Ideas Have Sex

**2.1.1 Evolution as accelerating combinations of ideas**

My all-time favorite TED Talk [When ideas have sex](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en)  by Matt Ridley presents evolution as the byproduct of sharing ideas: 

[![Matt Ridley](//airpair.github.io/img/2015/01/matt-ridley.png)](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en)
> ***"To answer our continual ability to attain more wealth and improve our own living standards, you need to understand how human beings bring together their brains, and enable their ideas to combine and recombine, to meet and indeed to mate."***

I totally recommend finding 15 minutes to absorb Ridley's talk. It is a framework for thinking around how this idea came about (AirPair + GitHub) as well as the millions of ideas we hope to spawn. One part Ridely explores that is particularly relevant to software, is the notion of our intellectual acceleration. The more we interact, converse and exchange knowledge, the more our ideas combine and mutate forming new ideas and products embodying previous ideas originating from thousands or even millions of individuals. 

![Stone Axe](http://iceagenow.info/wp-content/uploads/2011/11/Matt-Ridley-Stone-Axe.jpg)

Interestingly, as ideas become more evolved, they are even more quickly superseded. The Stone Axe was used for thousands of years, yet iPhones are now out of fashion within a few months.

![Mouse](http://iceagenow.info/wp-content/uploads/2011/11/Matt-Ridley-Computer-Mouse.jpg)

**2.1.2 GitHub => Social Coding**

As developers, we've seen hands down what Ridley is talking about. Every year the cycle of new frameworks appearing, spreading worldwide and becoming second best, gets shorter. 

Largely thanks to GitHub, Developer ideas having sex is old news. By removing friction for the common developer to wield Git, they made Open Source mainstream. I'm still awed and thankful to those GitHubbers who first empowered developers, who had never met, to collaborate, contribute, discuss and form bonds while improving common code.

** 2.1.3 AirPair => Social Authoring**

AirPair's whole thesis for existing, is observing a need around the acceleration of software ideas. As we make better software faster and faster, we'll need more efficient and powerful ways to express, share and consume the knowledge embedded in our code.

We're primarily known for connecting developers over video chat for live one-on-one help. Our broader mission is to find new ways to create relationships between developers that enable more efficient knowledge share. 

We think we've identified a gap that fits perfectly under why we wake up and come to work. Developers already have a universal ***long tail*** Q/A platform - *StackOverflow.com*. We have plenty of independent ***short tail*** content providers, who publish official go-to documentation on pure and vanilla use cases with their own Open Source frameworks and proprietary APIs. But where is the Wikipedia-like collection of quickstarts, tutorials and usage by example in the trenches? We think it doesn't exist yet, because no one has executed a collaborative model.

We'd like your playing out an experiment to reproduce for long form technical content what Stackoverflow did for Q/A and Wikipedia did for encyclopedia knowledge.

<!--Our new Git powered Posts section is aimed to enable  collaboration on more consolidated, refined and clearly expressed long form technical content than ever before. We all experienced the transformation journey GitHub took us on by ushering in the era of Social Coding. Now we'd like to reuse what they built mixed with a little AirPair spice and build out community based around passion for sharing developer knowledge and learning from one another.-->


### 2.2 Improving ROI on content investment

We had great success in our first 6 months pushing community posts. The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficked post has been read more than 200,000 times and our 24 hour record is 35,000 reads for a single post.

![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png)

The seeding phase was however, expensive and unsustainably heavy on internal manpower. To keep up the quality and pace encombent of our initial success, we needed to address the following concerns.

**2.2.1 Crowdsourcing more of our content production workflow**

Every publisher dreams of ***user generated content***  magically appearing on their site. From experience, we can tell you, great content takes time and energy. Before now, each post consumed almost 10 internal hours:

- Sourcing authors
- Considering proposals
- Editing, formatting & QA
- Marketing & promotion

We know there's no shortcut, so we're attempting to use GitHub and our review system distribute those hours across contributors. The community can now review, rate and help with QA. The best posts will organically bubble to top, which we will give extra internal marketing and promotional effort.

**2.2.2 Reducing content half life**

As an author devoting personal energy, or publisher commissioning content, ROI improves if what you publish stays relevant longer. We've covered how software moves exceptionally quick. The unfortunate byproduct is, software content decays exceptionally fast too.

Often the principals of a piece remain relevant, but as new framework versions emerge, it becomes unclear if the content is still useful.

Git provides a scalable way to maintain posts through forks and pull requests. It could even be used to tag and retrieve iterations of a post as relevant a specific framework version.

### 2.3 Ways GitHub Enhances The Author's Experience

*** Sharing editorial load ***

Editing is a particularly time and energy intensive process. The last 10% of changes usually require a disproportionate amount of time and are the least fun... The same git flow you know and love for code review can also empower fresh eyes to double-check your content and form so you can  focus more energy on the substance of your piece.

If you've always wanted to improve your writing, a portion of reviewers will be happy to help you express better grammar and style.

*** Discussing evolving ideas ***

GitHub issues, discussions and comment provide an amazing opportunity to get feedback that will force you to re-think the subject matter. Other influencers will help you reinforce arguments and even less advanced readers can help you simplify how you present concepts in clearer ways.

## 3 What we built

### 3.1 The AirPair live editor

TODO screenshots and short explanation of the editor.

Authors start posts in our live editor. Posts are written in markdown via the [ace web IDE](http://ace.c9.io/) by Cloud 9 and are refreshed in the browser as you type using the [marked library](https://github.com/chjj/marked"). While in draft, posts only exist in our database and do not have any git history. Once submitted to the community a git repo is created and HEAD represents the most up to date working copy of a post. Updates at this point go through git, so the editor requires a commit message each time you save. The actual displayed post still comes from our database. This enables us to let you "preview" before propagating changes to production.

### 3.2 How we store posts on GitHub

#### Private repos and private forks

When an author submits a post for community review, we create **a private repository on the [airpair organization](//github.com/airpair)** in which only the author has write permissions.

When a reader wants to contribute, they make **a private fork on their own github account**. ** Private forks do not count towards your private repo limits.

#### Adding users to the airpair organization and repo read/write teams

To facilitate the desired read/write permissions for different users, all users are added to the airpair github org and then to unique teams are created for each repo. Each repo has one team with write permissions for the author so that they may edit the post and pull request. The second team is created with read only permissions that allows contributors to fork and submit PRs without the ability to self merge. 

** Authors and readers unfortunately need to authenticate with repo privileges to facilitate this workflow.

### 3.3 Leveraging GitHub as much as possible

Especially for this first iteration, our aim was to leverage as much of the existing GitHub API and github.com UI as we could. GitHub already has rock solid discussion capabilities, merge tools and such. Leveraging as much as we could meant that we didn't have to reinvent the wheel and that we could take advantage of the fact that Developers are already familiar with the tooling. 

Althought there are advantaged to the AirPair live editor, once you fork a post as a contributor you have the option of doing nothing else on airpair.com and can work exclusively with your own environment and tool set.

### 3.4 Our 3-Step Publishing Workflow

All posts go through 3 sequential states:

> **1**. Draft

> **2**. Community Review

> **3**. Published

#### Draft

```javascript
// Properties of a post in draft
var draft = { 
  visibility: ['you'],
  contentStore: {
    workingCopy: 'airpair mongo instance',
    previewedCopy: 'is the working copy'    
  },
  authoring: {
    editWith: ['the airpair editor'],
    editRestrictions: ['the mongo id']
  }
}
```

New posts starts in ***Draft*** and are completely private. They have no git repo or history log. If you start something and your idea never goes anywhere, that experience was just for you. You can change everything as much as you like, so enjoy not taking things too seriously until you realize you want to.  


#### In Review

```javascript
// Properties of a post in review
var review = { 
  visibility: ['you', 'reviewers (logged in to airpair.com)'],
  contentStore: {
    workingCopy: 'github HEAD',
    previewedCopy: 'github HEAD',
    inReviewCopy: 'airpair mongo instance'    
  },
  authoring: {
    editWith: ['airpair editor', 'github.com', 'any tool you code with']
    editRestrictions: [
        'mongo id',
        'the repo name'],
    publishRestrictions: [
        '3 positivce reviews are required to publish'
    ]
  }
}
```

*** No turning back ***

When you submit your post we create a GitHub repo to begin tracking all changes via Git. Repo names across our org are unique and are locked once you submit,so make sure you are 100% happy when you submit.

***Visibility***

Congrats, your post is now visible to reviewers logged in to AirPair. It is still hidden from open traffic and makred as noindex just in case.

*** Where your posts lives and gets saved *** 

Once your post is submitted, you have to choice to continue editing on AirPair, or clone your repo and use any editor of your choosing. Either way, each time you save your post, including from the editor, it gets committed to master on github. The markdown appearing in the editor comes from HEAD and ***it will not appear on airpair.com until you publish changes from head back to AirPair**. This allows us to give you a preview feature without having to change your live copy. Although not quite semantically correct, you can think of HEAD as your working branch, and the copy stored in AirPair's mongo instance as your prod branch. 

#### Published

```javascript
// Properties of a post already published
var published = { 
  visibility: ['you', 'all logged in users', 'anonymous users', 'google', 'other bots'],
  contentStore: {
    workingCopy: 'github HEAD',
    previewedCopy: 'github HEAD',
    publishedCopy: 'airpair mongo instance'    
  },
  authoring: {
    editWith: ['airpair editor', 'github.com', 'any tool you code with']
    editRestrictions: [
        'mongo id',
        'tags',
        'title',        
        'repo name'],
    publishRestrictions: [        
        'A users with editor permissions must re-publish the post from HEAD if updates are ready'
        ]
    ]
  }
}
```

Published posts can take advantage of all the same forking and merging goodness as the review phase, with the exception the author needs an editor with permissions to update the live copy on AirPair. 

***Visibility***

Posts will appear at the top of our posts section and Rss feeds and will be fully index by google. Distiguished works will be promoted by AirPair's marketing team for additional exposure.

## 4 Conclusion

We hope this project is as impactful as we think it can. At AirPair we come to work each day focused on how we enable knowledge transfer from developer to another. We hope to see your posts and contributions.

If you haven't yet, now is a great time to check out our $100k Writing Competition.

[![$100k Developer Writing Competition](//www.airpair.com/static/img/pages/postscomp/og.png)](http://airpair.com/100k-writing-competition)

Drop us a line if you're excited about this or have some ideas about how to help us get this off the ground.
