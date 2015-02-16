<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1 A GitHub AirPair baby

### 1.1 TLDR; annoucement

Today I'm excited to annouce one of the more innovative projects I've been involed with. Pretty much anything part Git, or Octocat related is going to be cool. If you've already enjoyed AirPair posts, it gives me great pleasure knowing that our community content is about to get way more awesome. From today, you are invited to join our ***Social Authoring*** experiment as an author wanting to publish your own posts or reader interested in contributing to posts by others. Using our new *GitHub Powered Publishing Workflow*, authors and readers can work together using **Forks and Pull Requests** to produce better technical writing than every before.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

I'll intertwine many cool opportunties that make our new authoring setup significant, while covering why we integratd GitHub into our posts section and how we put the the workflow together. But before deep diving into details, here's a screenshot and some use cases to get you thinking:

> ![Fork a post on AirPair](/static/img/pages/posts/fork-post-dymo.png)

- Annoyed with that typo? ***Fork and fix***. 
- Spot a syntax error? ***Fork and fix***. 
- Code sample no longer runs with a new framework version? ***Fork and maintain***.
- Know a better way to do something? ***Fork and improve***.
- Disagree? ***Fork and discuss***.

### 1.2 In this post

**Section 1** covers a birds why care and how to start. **Section 2** explores philophical and practical discussion on why we and developers at large needed a Git powered collaborative blogging system. In **Section 3** I'll describe our implementation and how we pieced it together. Finally, **Section 4** will summarise what we hope to achieve and lead into our ***$100,000 Writing Competition***.

### 1.3 Social Authoring. What's in it for you?

Here's some pros we'll explore in more depth further down:  

**For readers**

- More proofed, comprehensive and up to date content than ever before
- Clear quality signals from our review system that a post is worth reading
- Ability to **contribute** small nuggets, without a comprehensive understanding required to author a whole post

**For authors** 

- Exposure to more readers and getting more feedback than publishing elsewhere
- Crowdsourced help improving your posts
- A forum to bounce and evolve whacky ideas before they become public
- Instant exposure for great work, without previously building traffic and following

### 1.4 Getting your hands dirty

- **[Starting a post](/posts/new)** is a piece of cake. 
- Forking is as easy as hitting the orange Fork button in the right rail.
- Review posts waiting for feedback anytime from the   [Posts in review](/posts/in-community-review) page.

<!-- *TODO mention sharing and put share widget here* -->

** 1.5 Bookmark this post **

We hope you like what you've seen so. You might consider using AirPair's bookmark feature for an easier way to return here later. 

## 2 Why Build Git Powered Publishing?


While writing this post, I kept thinking:

> "*How cool would it be if every page on the web were forkable?"*

This section covers a gamut of different forces that led us to combine the GitHub API with our existing authoring tools. Some of our motivations came from a sense that this could be groundbreaking. Maybe even evolutionary... Other guiding influences were simply marketing problems we needed to solve. Challenges that are probably relevant to everyone publishing on the web. Mostly though, we've had a great time working with our authors who inpired more than a million readers to come to AirPair in the last few months. Our main impetus was to make the experience of Authoring on AirPair easier and more impactful. We're thankful to have had great experiences so far from which to iterate on. To quote a friend who's tweet flew by mid-way through writing this post:

![Make things easier](//airpair.github.io/img/2015/01/making-things-easier.png)

### 2.1 When (Developer) Ideas Have Sex

**2.1.1 Evolution as accelerating combinations of ideas**

One reason I started AirPair, was because it's an expression of many ideas around learning from one another, presented in my all-time favorite TED Talk [When ideas have sex by Matt Ridley](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en): 

[![Matt Ridley](//airpair.github.io/img/2015/01/matt-ridley.png)](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en)
> ***"To answer our continual ability to attain wealth and improve our own living standards, you need to understand how human beings bring together their brains, and enable their ideas to combine and re-combine, to meet and indeed to mate."***

Totally recommend finidng 15 minutes to absorb Ridley's talk. It is a framework for thinking around how this idea came about as well as the millions of ideas we hope to spawn. One part Ridely explores that is particuarly relevant to software, is the notion of our intellectual acceleration. The more we interact, converse and exchange knowledge, the more our ideas combine and mutate forming new ideas and products embodying previous ideas originating from thousands or even millions of indivduals. 

![Stone Axe](http://iceagenow.info/wp-content/uploads/2011/11/Matt-Ridley-Stone-Axe.jpg)

Interestingly, as ideas become more evolved, they are even more quickly supersceded. The Stone Axe was used for thousands of years, yet iPhones are out of fasion after a few months.

![Mouse](http://iceagenow.info/wp-content/uploads/2011/11/Matt-Ridley-Computer-Mouse.jpg)

**2.1.2 GitHub => Social Coding**

As developers, we've see hands down what Ridley is talking about. Every year the cycle of new frameworks appearing, spreading world-wide and becoming second best, gets shorter. 

Largely thanks to GitHub, Developer ideas having sex is old news. By removing friction for the common developer to wield Git, they made Open Source mainstream. I'm still awed and thankful to those GitHubbers who first empowered developers, who had never met, to collaborate, contribute, discuss and form bonds while improving common code.

** 2.1.3 AirPair => Social Authoring**

AirPair's whole thesis for existing, is observing a need around the acceleration of software ideas. As we make better software faster and faster, we'll need more efficient and powerful ways to express, share and consume the knowledge emedded in our code.

We're primarily known for connecting developers over video chat for live one-on-one help. Our broader mission is to find new ways to create relationships between developers that enable more efficient knowledge share. 

We think we've identified a gap that fits perfectly under why we wake up and come to work. Developers already have a universal ***long tail*** Q/A platform - *StackOverflow.com*. We have plenty of independent ***short tail*** content providers, who publish official go-to documentation on pure and vanilla use cases with their own Open Source frameworks and proprietary APIs. But where is the Wikipedia-like collection of quickstarts, tutorials and usage by example in the trenches? We think it doesn't exist yet, because no one has executed a collabortive model.

We'd like your playing out an experiment to reproduce for long form technical content what Stackoverflow did for Q/A and Wikipedia did for encyclopedia knowledge.

<!--Our new Git powered Posts section is aimed to enable  collaboration on more consolidated, refined and clearly expressed long form technical content than ever before. We all experienced the transformation journey GitHub took us on by ushering in the era of Social Coding. Now we'd like to reuse what they built mixed with a little AirPair spice and build out community based around passion for sharing developer knowledge and learning from one another.-->


### 2.2 Improving ROI on content investment

We had great success in our first 6 months pushing community posts. The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficed post has been read more than 200,000 times and our 24 hour record is 35,000 reads for a single post.

![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png)

The seeding phase was however, expensive and unsustainably heavy on internal manpower. To keep up the quality and pace encombent of our initial success, we needed to addres the following concerns.

**2.2.1 Crowdsourcing more of our content production workflow**

Every publisher dreams of ***user generated content***  magically appearing on their site. From experience, we can tell you, great content takes time and energy. Before now, each post consumed almost 10 internal hours:

- Sourcing authors
- Considering proposals
- Editing, formating & QA
- Marketing & promotion

We know there's no shortcut, so we're attempting to use GitHub and our review system distribute those hours across contributors. The community can now review, rate and help with QA. The best posts will organically bubble to top, which we will give extra internal marketing and promotional effort.

**2.2.2 Reducing content half life**

As an author devoting personal energy, or publisher comissioning content, ROI improves if what you publish stays relevant longer. We've covered how software moves exceptionally quick. The unfortunate bi-product is, software content decays exeptional fast too.

Often the principals of a piece remain relevant, but as new framework versions emerge, it becomes unclear if the content is still useful.

Git provides a scalable way to maintenace posts through forks and pull requests. It could even be used to tag and retrieve iterations of a post as relevant a specific framework version.

### 2.3 Ways GitHub Enhances The Author's Experience

*** Sharing editoral load ***

Editing a particuarly time and energy intensive procecess. The last 10% of changes usually require a disproportionate amount of time and are the least fun... The same git flow you know and love for code review can also empower fresh eyes to double-check your content and form so you can  focus more energy on the substance of your piece.

If you've always wanted to improve your writing, a portion of reiewers will be happy to help you express better grammar and style.

*** Discussing evolving ideas ***

GitHub issues, discussions and comment provide an amazing opportunity to get feedback that will force you to re-think the subject matter. Other influencers will help you re-inforce arguments and even less advanced readers can help you simplify how you present concepts in clearer ways.

## 3 What we built

### 3.1 AirPair's live editor

TODO screenshots and short explanation of the editor.

Authors start their posts in our live editor. Posts are written in markdown via the ace web editor and refreshed as you type using the marked library.

### 3.2 How we store posts on GitHub

When an author decides their posts is ready for community review, we create a private repository on the airpair organization. The repos need to be private so not to destroy our SEO. Once the repo is created all saves by the author from the AirPair editor go through the master repo.

When an reader decides they want to contribute, the make a private fork that sits on their own github account. Private forks do not count towards your private repo limits.

To faciliate the necessary permissions we ask you to authenticate your github account with repo privilages. This allows us to add the author to our organization, and then to unique team created just for the purpose of having write permissions to the main repo on our organization. For the contributors, we use the repo permissions to create your fork.

### 3.3 Our 3-Step V1 Workflow

Our goal was leverage as much of the existing GitHub API and github.com UI as possible because. GitHub already rock solid discussion UI, merge tools and such. Plus Developers are already familiar. Once you fork a post you have the option of doing nothing futher on airpair.com if you prefer to work exclusively in your own environment.

All posts basically go through 3 sequential states:

> **1**. Draft

> **2**. Community Review

> **3**. Published

#### Draft

`touch Fun-and-games.md`

When you create a new post, it starts in ***Draft***. While in draft your post is only visible to you. It has no git history and we simply save your changes back to our mongo. If you start something and your idea never goes anywhere, that experience was just for you, so enjoy not taking things too seriously until you realize you want to.

*** No turning back ***

As you go to submit your post, you will be prompted to authenticate with GitHub repo privilages. This is because this is the moment when things get real. We take the repo name you provide (which you cannot change later) and spin up a private repository on the github.com/airpair org. Repo permissions allow us to add you to "The Author" team on your repository. Thus, besides god users in the airpair org, you are the only one with write access to accept and merge or reject pull requests coming in for your contributors forks.

As discussed in the next state, the rules of the game change when you hit, so pay attention, it's worth understanding how things work before you push that button!

*** Properties of the *draft* state ***

```javascript
var draft = { 
  visibility: ['just you'],
  contentStore: {
    workingCopy: 'airpair db',
    previewedCopy: 'airpair db'    
  },
  authoring: {
    editWith: ['only by the airpair editor'],
    restrictions: ['everything is editable, except the mongo id']
  }
}
```

#### In Review

*** Where your content lives and gets saved *** 

Once your post is submitted, you have to choice to continue editing on AirPair, or clone your repo and use your normal tools. Either way each time you save your post including from the editor it gets committed to master on github. The markdown appearing in the edidot actually comes from HEAD on github and will not appear on airpair.com until you hit ***Propagate HEAD***. 

***Visibility***

Congrats, your post is now visible to anyone logged in to AirPair. You meant to do that right? Well relax, it's makred as noindex, follow so only hardcore contributors that want to take the time to be invovled in unfinished work will look at it. It also won't get imortalized in google's memeory until it's published. 

***Properties of the *review* state***

```javascript
var review = { 
  visibility: ['you', 'logged in users'],
  contentStore: {
    workingCopy: 'github HEAD',
    previewedCopy: 'airpair db',
    inReviewCopy: 'airpair db',    
  },
  authoring: {
    editWith: ['airpair editor', 'any tool you like is just a clone away']
    restrictions: [
        ['the repo name is used as a unique slug makes up part of your posts public url, its locked in so make sure you are happy when you submit',
        'A minimum number of reviews & minimum rating is required to publish your post']
    ]
  }
}
```

#### Published

```javascript
var review = { 
  visibility: ['you', 'logged in users', 'anonymous users', 'google', 'other bots'],
  contentStore: {
    workingCopy: 'github HEAD',
    previewedCopy: 'github HEAD',
    publishedCopy: 'airpair db',     
  },
  authoring: {
    edits: ['airpair editor', 'any tool you like is just a clone away']
    restrictions: [
        ['the repo name / slug',
         'everything other than the content is no longer editable',
         'Only AirPair users with editor permissions can propagate github HEAD to the published version on airpair.com'
        ]
    ]
  }
}
```

## 4 Conclusion

We hope this project is as impactful as we think it can be and that news of these tools spread through the developer world. At AirPair we come to work each day focused on how we can make a company thrive around enabling knowledge transfer from developer to another. We hope to see your posts and contributions. Thanks for stopping by.
