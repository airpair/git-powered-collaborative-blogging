<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1 Filling a gap with Social Authoring

Developers already have a universal go-to ***long tail*** knowledge source, thanks to StackOverflow's successful social Q/A platform. We also have a plethora of high quality independent ***short tail*** knowledge repositories, thanks to investments in official documentation by Open Source framework contributors and proprietary API providers. 

<!-- TODO Tinsert screenshots of stackoverflow, AngularJS docs & keen.io here -->

But what about ***medium tail*** Software knowledge? Independently produced quickstarts, tutorials and tales of production horros and success already exist scattered on blogs across the web. But we think there's room and would argue a growing necessity, for a consolidated Wikipedia-like resource of superior quality medium tail software content. 

Sounds obvious... So why doesn't it exist already? We think it's because no one has successfully executed a social, collaborative model.

### 1.1 Announcing Social Authoring on AirPair

Today I'm excited to share one of the more innovative projects I've been involved with. Pretty much anything part Git, or Octocat related is going to be cool. If you've already enjoyed AirPair's posts section, it gives me great pleasure knowing that our community content is about to get way more awesome. From today, you are invited to join our ***Social Authoring*** experiment as an author wanting to publish your own posts, or reader interested in contributing to posts by others using **Forks and Pull Requests**.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

With our new *GitHub Powered Publishing Workflow*, we hope to enable collaboration that will produce more accurate and refined technical writing than ever before. In this post, I'll cover how we integrated GitHub into our posts section and intertwine many cool opportunities that make our new authoring setup significant. We'll end leading into our ***$100,000 Developer Writing Competition***, but before diving into details, here's a screenshot to get you thinking:

![Fork a post on AirPair](//airpair.github.io/img/2015/01/fork-examples.png)

We think readers are going to love:  

- More proofed, comprehensive and up to date technical content than ever before
- Clear quality signals from our rating system
- The **ability to contribute** without the time or understanding required to author a whole post

We think authors are going love:  

- Exposure to more feedback than publishing elsewhere
- Crowdsourced help improving post quality
- A forum to bounce whacky ideas before they become public
- Instant exposure for great posts, without peviously amassing a personal following

### 1.2 How to get involved

- **[Staring a post](/posts/new)** is a piece of cake
- To Fork just hit the orange *Fork* button in the right rail
- Give feedback with the review widget at the bottom of each post
- Help Q/A and shape [Posts in review](/posts/in-community-review) before they get published
- Bookmark this post if you want to come back to it later

## 2 Why we built Git Powered Publishing

There are a gamut of different forces that led us to combine the GitHub API with our existing authoring tools. (2.1) Some motivations came from a sense that this could be groundbreaking. Indeed even evolutionary... (2.2) Other guiding influences were driven by marketing problems we needed to solve. (2.3) Mostly though, we've had a great time working with our authors who inspired more than a million readers to visit AirPair in the last few months. Our main impetus was to make their authoring experience easier and more impactful than publishing developer content anywhere else.

### 2.1 When (Developer) Ideas Have Sex

**2.1.1 Evolution as accelerating combinations of ideas**

My all-time favorite TED Talk [When ideas have sex](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en)  by Matt Ridley presents evolution as the byproduct of sharing ideas: 

[![Matt Ridley](//airpair.github.io/img/2015/01/matt-ridley.png)](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en)
> ***"To answer our continual ability to attain more wealth and improve our own living standards, you need to understand how human beings bring together their brains, and enable their ideas to combine and recombine, to meet and indeed to mate."***

I can't recommend enough, to set aside 15 minutes to absorb Ridley's talk. It's both a framework for thinking of how this idea came about (AirPair + GitHub) as well as the millions of ideas we hope to spawn. 

One part Ridley explores that is particularly relevant to software, is the notion of our intellectual acceleration. The more we interact, converse and exchange knowledge, the more our ideas combine and mutate forming new ideas and products embodying previous ideas originating from thousands or even millions of individuals. 

![Stone Axe](http://iceagenow.info/wp-content/uploads/2011/11/Matt-Ridley-Stone-Axe.jpg)

Interestingly, as ideas become more evolved, they are even more quickly superseded. The Stone Axe was used for thousands of years, yet iPhones are now out of fashion within a few months.

![Mouse](http://iceagenow.info/wp-content/uploads/2011/11/Matt-Ridley-Computer-Mouse.jpg)

**2.1.2 GitHub => Social Coding**

As developers, we've seen hands down what Ridley is talking about. Every year the cycle of new frameworks appearing, spreading worldwide and becoming second best, gets shorter. 

Largely thanks to GitHub, Developer ideas having sex is old news. By removing friction for the common developer to wield Git, they made Open Source mainstream. I'm still awed and thankful to those GitHubbers who first empowered developers, who had never met, to collaborate, contribute, discuss and form bonds while improving common code.

** 2.1.3 AirPair => Social Authoring**

AirPair's thesis for existing, is an observation around the acceleration of software ideas. *As we make better software faster and faster, we'll need more efficient and powerful ways to express, share and consume the knowledge embedded in our code.*

We're primarily known for connecting developers over video chat for live one-on-one help. But our broader mission is to find new ways to create relationships between developers that enable more efficient knowledge share. 

We've decided to run an experiment and see if we can reproduce for long form technical content, what Stackoverflow did for Q/A and Wikipedia did for encyclopedic knowledge.

<!--Our new Git powered Posts section is aimed to enable  collaboration on more consolidated, refined and clearly expressed long form technical content than ever before. We all experienced the transformation journey GitHub took us on by ushering in the era of Social Coding. Now we'd like to reuse what they built mixed with a little AirPair spice and build out community based around passion for sharing developer knowledge and learning from one another.-->


### 2.2 Improving ROI on content investment

We had great success in our first 6 months pushing community posts. The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficked post has been read more than 200,000 times and our 24 hour record is 35,000 reads for a single post.

![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png)

The seeding phase was however, expensive and unsustainably heavy on internal manpower. To keep up the quality and pace incumbent of our initial success, we needed to address the following concerns.

**2.2.1 Crowdsourcing more of our content production workflow**

Every publisher dreams of ***user generated content***  magically appearing on their site. From experience, we can tell you, great content takes time and energy. Before now, each post consumed almost 10 internal hours:

- Sourcing authors
- Considering proposals
- Editing, formatting & QA
- Marketing & promotion

We know there's no shortcut, so we're attempting to use GitHub and our review system to distribute those hours across contributors. The community can now review, rate and help with QA. The best posts will organically bubble to the top, so we can give them extra internal marketing and promotional effort.

**2.2.2 Reducing content half life**

As an author devoting personal energy, or publisher commissioning content, ROI improves if what you publish stays relevant longer. We've covered how software moves exceptionally quick. The unfortunate byproduct is, software content decays exceptionally fast too.

Often the principals of a piece remain relevant, but as new framework versions emerge, it becomes unclear if the content is still useful.

Git provides a scalable way to maintain posts through forks and pull requests. It could even be used to tag and retrieve iterations of a post as relevant a specific framework version.

### 2.3 Ways GitHub Enhances The Author's Experience

*** Sharing editorial load ***

Editing is a particularly time and energy intensive process. The last 10% of changes usually require a disproportionate amount of time and are the least fun... The same git flow you know and love for code review can also empower fresh eyes to double-check your content and form so you can  focus more energy on the substance of your piece.

If you've always wanted to improve your writing, a portion of reviewers will be happy to help you express better grammar and style.

*** Discussing evolving ideas ***

GitHub issues, discussions and comments provide an amazing opportunity to get feedback that will force you to re-think the subject matter. Other influencers will help you reinforce arguments and even less advanced readers can help you simplify how you present concepts in clearer ways.

## 3 What we built

### 3.1 The AirPair live editor

TODO screenshots and short explanation of the editor.

Authors start posts in our live editor. Posts are written in markdown via the [ace web IDE](http://ace.c9.io/) by Cloud 9 and are refreshed in the browser as you type using the [marked library](https://github.com/chjj/marked"). While in draft, posts only exist in our database and do not have any git history. Once submitted to the community, a git repo is created and HEAD represents the most up to date working copy of a post. Updates at this point go through git, so the editor requires a commit message each time you save. The actual displayed post still comes from our database. This enables us to let you "preview" before propagating changes to production.

### 3.2 How we store posts on GitHub

#### Private repos and private forks

When an author submits a post for community review, we create **a private repository on the [airpair organization](//github.com/airpair)** in which only the author has write permissions.

When a reader wants to contribute, they make **a private fork on their own github account**. ** Private forks do not count towards your private repo limits.

#### Adding users to the airpair organization and repo read/write teams

To facilitate the desired read/write permissions for different users, all users are added to the airpair github org and then to unique teams are created for each repo. Each repo has one team with write permissions for the author so that they may edit the post and pull request. The second team is created with read only permissions that allows contributors to fork and submit PRs without the ability to self merge. 

** Authors and readers unfortunately need to authenticate with repo privileges to facilitate this workflow.

### 3.3 Leveraging GitHub as much as possible

Especially for this first iteration, our aim was to leverage as much of the existing GitHub API and github.com UI as we could. GitHub already has rock solid discussion capabilities, merge tools and such. Leveraging as much as we could meant that we didn't have to reinvent the wheel and we could take advantage of the fact that Developers are already familiar with the tooling. 

Althought there are advantages to the AirPair live editor, once you fork a post as a contributor you have the option of doing nothing else on airpair.com and can work exclusively with your own environment and tool set.

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

Congrats, your post is now visible to reviewers logged in to AirPair. It is still hidden from open traffic and marked as noindex just in case.

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

We hope this project is as impactful as we think it can be. At AirPair we come to work each day focused on how we enable knowledge transfer from developer to another. We hope to see your posts and contributions.

If you haven't yet, now is a great time to check out our $100k Writing Competition.

[![$100k Developer Writing Competition](//www.airpair.com/static/img/pages/postscomp/og.png)](http://airpair.com/100k-writing-competition)

Drop us a line if you're excited about this or have some ideas about how to help us get this off the ground.
