<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1 Filling a gap with Social Authoring

Thanks to StackOverflow's *Social Q&A* platform, we have a reliable,
universal go-to for ***long tail*** software knowledge. "Long tail", meaning niche, often obsure things that need to be expressed in lots of words like "Ace Editor onChange event rendering performance with AngularJS". On the **short** end of the spectrum, docs by Open Source creators and API companies provide excellent answers for most queries like "AngularJS Directive". 

But what about questions in between, like "How to Build a mobile chat
system with Firebase?" or "Should I use AngularJS or Ember?". Independent
posts scattered across the web are our best tools for answering ***medium
tail*** queries like these. Unfortunately, unless you recognize an
author, it can be hard to know if you're about to read the best or even a good peice on a given subject matter.

Writing high quality ***long form technical content is hard***... and even
harder to maintain. Yet with the accceleration of new frameworks spawning, ***there's necessity to cover more permutations of medium tail software
knowledge *** with better tutorials, examples of technology in
production and expert guides. 

The Social thing to work for Q&A on Stackoverflow. The Social thing worked for coding on GitHub. Can we step **authoring** up a notch with some social magic?

### 1.1 Announcing Social Authoring on AirPair

Pretty much anything part Git, or Octocat related is going to be cool. If
you've already enjoyed some of the epic community posts that have gone viral on 
AirPair, it gives me great pleasure knowing from today our community content is 
about to get way more awesome, as ***authors can now work with
readers using Forks and Pull Requests***.

With our new *GitHub Powered Workflow*, we hope to usher collaboration
that will enable more accurate and refined technical writing than ever
before.

![Collaborate on post using
Git](/static/img/pages/posts/authoring-flow.png)

In this post, I'll cover how we integrated GitHub and many of the cool 
opportunities that make our new authoring setup significant. We'll end leading 
into our ***$100,000 Developer Writing Competition***. 

Before diving into details, here's a screenshot to get you thinking:

![Fork a post on
AirPair](//airpair.github.io/img/2015/01/fork-examples.png)

### 1.2 Benefits of Social Authoring

Readers are going to love  

- More proofed, comprehensive and up to date technical content than ever
before 
- Clear quality signals on which posts to read
- The **ability to contribute** small bytes, without the time or understanding
required to author a whole post

Authors are going love

- Exposure to more feedback than publishing elsewhere
- Crowdsourced help improving post quality
- A forum to bounce whacky ideas before they become public
- Instant exposure for great posts (without needing a personal
following)

### 1.3 Getting involved

- **[Staring a post](/posts/new)** is a piece of cake and everything is
private until you submit to the community.  
>[![Star a
post](//airpair.github.io/img/2015/02/start-post.png)](/posts/new)

- To fork, hit the orange *fork* button in the right rail
>[![Review a
post](//airpair.github.io/img/2015/02/fork-button.png)](#review)

- Give feedback with the review widget at the bottom of each post
>[![Review a
post](http://airpair.github.io/img/2015/02/review-post.png)](#review)

- Help Q/A and vet [Posts in review](/posts/in-community-review) waiting
to get published

- Bookmark this post if you want to come back to it later

## 2 Why Power Publishing with Git

There are a gamut of forces that led us to integrate the GitHub API with
our existing authoring tools. In `2.1` I'll cover *philosophically* how we
think combining Git with long form technical blogging can be evolutionary for 
the developer community... In `2.2` I'll touch on content marketing *economics*
believe Git will help us (and potentially many others) solve. Mostly though, we
wanted thank the authors who inspired more than a million readers to visit
AirPair in the last few months by making the authoring *user experience*
easier, more fun and more impactful (which I'll explore in`2.3`).

### 2.1 When (Developer) Ideas Have Sex

I can't recommend enough: set aside 15 minutes to absorb my all-time
favorite TED Talk - [When ideas have
sex](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en) - 
by Matt Ridley.

[![Matt
Ridley](//airpair.github.io/img/2015/01/matt-ridley.png)](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en)
> The short version

> **Ridley presents evolution as an accelerating byproduct of
sharing ideas:**

> *"To answer our continual ability to attain more wealth and improve our
own living standards, you need to understand how human beings bring together
their brains, and enable their ideas to combine and recombine, to meet and
indeed to mate."*


One part Ridley covers that is particularly relevant to software, is the notion
of our ***intellectual acceleration***. The more we interact, converse and
exchange knowledge, the more our ideas combine and mutate forming new ideas and
products. Things you and I conceive day to day as single ideas, actually embody
previous ideas originating from thousands or even millions of individuals.

![Stone
Axe](//airpair.github.io/img/2015/02/matt-ridley-stone-axe.jpg) 

Interestingly, as ideas become more evolved, they are even more quickly
superseded. The Stone Axe was used for thirty thousand years, yet iPhones are
now out of fashion within a few months.

![Mouse](//airpair.github.io/img/2015/02/matt-ridley-computer-mouse.jpg) 

** 2.1.1 (Developer) Intellectual Acceleration **

As developers, we've seen hands down what Ridley is talking about. Every year
the cycle of new frameworks appearing, spreading worldwide and becoming second
best, gets shorter. Largely thanks to GitHub making Open Source mainstream,
*Developer ideas having sex* is old news. 

AirPair's thesis for existing, is around an observation. *As we make better
software faster and faster, we'll need more efficient and powerful ways to
express, share and consume the knowledge embedded in our code.*

** 2.1.2 Socially creating better content faster **

We're primarily known for connecting developers over
video chat for live one-on-one help. But our broader mission is to find new
ways to create relationships between developers that enable more efficient
knowledge share. So with our mission in mind, we decided to run an experiment
and see if we can reproduce what Stackoverflow did for Q/A and
Wikipedia did for long-form encyclopedic content using the tools GitHub used
to usher the era of Social Coding.

<!--** todo insert illustration ** -->

### 2.2 Improving ROI on

content investment We had great success in our first 6 months pushing
community posts. The average post published on AirPair in January 2015
received more than 15,000 views. Our most trafficked post has been read more
than 200,000 times and our 24 hour record is 35,000 reads for a single post.
![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png) The
seeding phase was however, expensive and unsustainably heavy on internal
manpower. To keep up the quality and pace incumbent of our initial success, we
needed to solve the following challenges. **2.2.1 Reduce internal time per
post** Every publisher dreams of ***user generated content*** magically
appearing. From experience, we can tell you, great content takes time and
energy. During our seed phase, each post consumed around 10 hours from our
team. There's no shortcut, so we're attempting to use GitHub and new our
review system to crowdsource many of those hours across contributors. **2.2.2
Reduce content half life** We've covered how software moves exceptionally
quick. The unfortunate byproduct is, software content decays exceptionally
fast too. Often the principals of a piece remain relevant, but as new
framework versions emerge, it becomes unclear if the content is still useful.
Maintaining content against moving code bases is an unwiedly endevour. Git
provides a way to collaboratively maintain posts through forks and pull
requests. It can even be used to tag and retrieve iterations relevant to a
specific framework versions. ### 2.3 Gaining an edge The Authoring Experience
** 2.3.1 Sharing editorial load with Pull Requests ** Editing is a
particularly time and energy intensive process. The last 10% of changes
usually require a disproportionate amount of time and are the least fun... The
same git flow you know and love for code review can also empower fresh eyes to
double-check your content and form so you can  focus more energy on the
substance of your piece. If you've always wanted to improve your writing, a
portion of reviewers will be happy to help you express better grammar and
style. ** 2.3.2 Discussing evolving ideas with Github Comments ** GitHub
issues, discussions and comments provide an amazing opportunity to get
feedback that will force you to re-think the subject matter. Other influencers
will help you reinforce arguments and even less advanced readers can help you
simplify how you present concepts in clearer ways. ## 3 What we built ### 3.1
The AirPair live editor TODO screenshots and short explanation of the editor.
Authors start posts in our live editor. Posts are written in markdown via the
[ace web IDE](http://ace.c9.io/) by Cloud 9 and are refreshed in the browser
as you type using the [marked library](https://github.com/chjj/marked"). While
in draft, posts only exist in our database and do not have any git history.
Once submitted to the community, a git repo is created and HEAD represents the
most up to date working copy of a post. Updates at this point go through git,
so the editor requires a commit message each time you save. The actual
displayed post still comes from our database. This enables us to let you
"preview" before propagating changes to production. ### 3.2 How we store posts
on GitHub #### Private repos and private forks When an author submits a post
for community review, we create **a private repository on the [airpair
organization](//github.com/airpair)** in which only the author has write
permissions. When a reader wants to contribute, they make **a private fork on
their own github account**. ** Private forks do not count towards your private
repo limits. #### Adding users to the airpair organization and repo read/write
teams To facilitate the desired read/write permissions for different users,
all users are added to the airpair github org and then to unique teams are
created for each repo. Each repo has one team with write permissions for the
author so that they may edit the post and pull request. The second team is
created with read only permissions that allows contributors to fork and submit
PRs without the ability to self merge.  ** Authors and readers unfortunately
need to authenticate with repo privileges to facilitate this workflow. ### 3.3
Leveraging GitHub as much as possible Especially for this first iteration, our
aim was to leverage as much of the existing GitHub API and github.com UI as we
could. GitHub already has rock solid discussion capabilities, merge tools and
such. Leveraging as much as we could meant that we didn't have to reinvent the
wheel and we could take advantage of the fact that Developers are already
familiar with the tooling.  Althought there are advantages to the AirPair live
editor, once you fork a post as a contributor you have the option of doing
nothing else on airpair.com and can work exclusively with your own environment
and tool set. ### 3.4 Our 3-Step Publishing Workflow All posts go through 3
sequential states: > **1**. Draft > **2**. Community Review > **3**. Published
#### Draft ```javascript // Properties of a post in draft var draft = {   
visibility: ['you'],   contentStore: {     workingCopy: 'airpair mongo
instance',     previewedCopy: 'is the working copy'       },   authoring: {   
 editWith: ['the airpair editor'],     editRestrictions: ['the mongo id']
  }
}
```

New posts starts in ***Draft*** and are completely private. They have no git
repo or history log. If you start something and your idea never goes anywhere,
that experience was just for you. You can change everything as much as you
like, so enjoy not taking things too seriously until you realize you want to. 
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

When you submit your post we create a GitHub repo to begin tracking all
changes via Git. Repo names across our org are unique and are locked once you
submit,so make sure you are 100% happy when you submit. ***Visibility***

Congrats, your post is now visible to reviewers logged in to AirPair. It is
still hidden from open traffic and marked as noindex just in case.
*** Where your posts lives and gets saved *** 

Once your post is submitted, you have to choice to continue editing on
AirPair, or clone your repo and use any editor of your choosing. Either way,
each time you save your post, including from the editor, it gets committed to
master on github. The markdown appearing in the editor comes from HEAD and
***it will not appear on airpair.com until you publish changes from head back
to AirPair**. This allows us to give you a preview feature without having to
change your live copy. Although not quite semantically correct, you can think
of HEAD as your working branch, and the copy stored in AirPair's mongo
instance as your prod branch.  #### Published ```javascript // Properties of a
post already published var published = {    visibility: ['you', 'all logged in
users', 'anonymous users', 'google', 'other bots'],   contentStore: {    
workingCopy: 'github HEAD',     previewedCopy: 'github HEAD',    
publishedCopy: 'airpair mongo instance'       },
  authoring: {
    editWith: ['airpair editor', 'github.com', 'any tool you code with']
    editRestrictions: [
        'mongo id',
        'tags',
        'title',        
        'repo name'],
    publishRestrictions: [        
        'A users with editor permissions must re-publish the post from HEAD if
updates are ready'         ]
    ]
  }
}
```

Published posts can take advantage of all the same forking and merging
goodness as the review phase, with the exception the author needs an editor
with permissions to update the live copy on AirPair.  ***Visibility***

Posts will appear at the top of our posts section and Rss feeds and will be
fully index by google. Distiguished works will be promoted by AirPair's
marketing team for additional exposure. ## 4 Conclusion

We hope this project is as impactful as we think it can be. At AirPair we come
to work each day focused on how we enable knowledge transfer from developer to
another. We hope to see your posts and contributions. If you haven't yet, now
is a great time to check out our $100k Writing Competition.
[![$100k Developer Writing
Competition](//www.airpair.com/static/img/pages/postscomp/og.png)](http://airpair.com/100k-writing-competition)
Drop us a line if you're excited about this or have some ideas about how to
help us get this off the ground.