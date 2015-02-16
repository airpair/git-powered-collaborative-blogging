<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1 A GitHub AirPair baby

### 1.1 TLDR; annoucement

Today I'm excited to annouce one of the more innovative projects I've been involed with. Pretty much anything part Git, or Octocat related is going to be cool. If you've already enjoyed AirPair posts, it gives me great pleasure knowing that our community content is about to get way more awesome. From today, you are invited to join our ***Social Authoring*** experiment as an author wanting to publish your own posts or reader interested in contributing to posts by others. Using our new *GitHub Powered Publishing Workflow*, authors and readers can work together wikipedia-style to produce better technical writing than every before using **Forks and Pull Requests**.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

I'll intertwine many other cool opportunties that make our new authoring setup significant, while covering why we built it and how we put the the publishing flow together. But before deep diving into details, here's a screenshot and some use cases to get you thinking:

> ![Fork a post on AirPair](/static/img/pages/posts/fork-post-dymo.png)

- Annoyed with that typo? ***Fork and fix***. 
- Spot a syntax error? ***Fork and fix***. 
- Code sample no longer runs with a new framework version? ***Fork and maintain***.
- Know a better way to do something? ***Fork and improve***.
- Disagree? ***Fork and discuss***.

### 1.2 In this post

**Section 1** covers a birds eye view of what we're doing. **Section 2** explores philophical and practical discussion on why we and developers at large needed a Git powered community blog-like system. In **Section 3** I'll describe what our implementation looks like and how we pieced it together. Finally, **Section 4** will summarise what we hope to achieve and lead into our ***$100,000 Writing Competition***.

### 1.3 Social Authoring. What's in it for you?

Here's some pros we'll explore in more depth, further down:  

**For readers**

- More proofed, comprehensive and up to date content than ever before
- Clear quality signals from our review system that a post is worth reading
- Ability to **contribute** small nuggets, without a comprehensive understanding required to author a whole post

**For authors** 

- Exposure to more readers than publishing on your own
- More feedback
- Crowdsourced help improving your posts
- A forum to bounce and evolve whacky ideas before they become public
- Instant exposure for great work, without aquiring a prior following

### 1.4 Getting your hands dirty


- [Starting a post](/posts/new) is a piece of cake. 
- Forking is as easy as hitting the orange 'Fork this post' button in the right rail. Try it :)
- Review posts waiting for feedback anytime from the   [Posts in review](/posts/in-community-review) page.

<!-- *TODO mention sharing and put share widget here* -->

#### 1.5 Bookmark this post

We hope you like what you've seen so far and are wanting to read on. You might consider using AirPair's bookmark feature for an easy way to return to this post later - *it is a lengthy read!* 

## 2 Why Build Git Powered Publishing?


While writing this post, I keep thinking:

> *How cool would it be if everything on the web were forkable?*

This section covers a gamut of different forces that led us to integrate the GitHub API with our existing authoring tools. Some of our motivations came from a sense that this could be groundbreaking and indeed evolutionary... Other guiding influences were simply marketing problems we needed to solve, challenges that are probably relevant to every publisher on the web. Mostly though, we've had a great time working with our authors. We thank you guys deeply for inpiring more than a million readers to come to AirPair in the last few months. The majority of our motivation came from the disire to make it easier and more impactful for authors publishing with us. To quote a friend who's tweet came to me mid way through writing this post:

![Make things easier](//airpair.github.io/img/2015/01/making-things-easier.png)

### 2.1 When (Developer) Ideas Have Sex

`touch A-Sprinkle-of-TED-Magic.mov`

**2.1.1 Evolution as accelerating combinations of ideas**

One reason I started AirPair, was because it's an expression of many ideas presented in my all-time favorite TED Talk [When ideas have sex by Matt Ridley](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en). The main theme is Ridleys explanation for humanity's consisten historical progression in terms of living condition and wealth: 

![Matt Ridley](//airpair.github.io/img/2015/01/matt-ridley.png)
> ***"To answer that question, you need to understand how human beings bring together their brains, and enable their ideas to combine and re-combine, to meet and indeed to mate."***

One part Ridely explores that is particuarly relevant to software, is the notion of intellectual acceleration. The more we interact, converse and exchange knowledge, the more our ideas combine and mutate forming new ideas and products embodying previous ideas originating from thousands or millions of indivduals. Interestingly, as ideas become more evolved, they are even more quickly supersceded. The Stone Axe was used for thousands of years, yet the computer mouse stayed relevant for only a few.

**2.1.2 GitHub => Social Coding**

`touch Ode-to-Octocat.git`

You're a developer, so you've see hands down what Ridley is talking about. Every year  the cycle of new frameworks appearing, spreading world-wide and becoming second best, gets shorter. 

Developer ideas having sex is old news, largely thanks to GitHub. By building great UI that removed friction for the common developer to wield git, they made open source mainstream. Now we programmers are a particular intellectually promiscous bunch. I'm still awed and thankful to those GitHubbers who first empowered developers, that had never met, to collaborate, contribute, discuss and form bonds while improving code which represented a common interest.

*By deduction though, it seems, we may have an upcoming challenge to solve. If we're going to make better software faster and faster, we'll need more efficient and powerful tools to express and share the ideas embedded in our software.*

** 2.1.3 AirPair => Social Authoring**

`touch git-powered-publishing-elevator-pitch.wav`

AirPair's is known primarily for connecting developers over video chat for one-on-one help. This is one expression of our broader mission - to find new ways to connect developers, create relationships and enable knowledge sharing.

We think there's a gap, and the software world needs a Wikipedia like collection of quickstarts, tutorials and thought pieces. We already have a universal *long tail* content platform - StackOverflow.com. There's also plentry of independent *short tail* content providers, encompasing open-source contributors and companies that product their own technology and documentation to go with. But where's the universal **medium-tail** wiki of 'how to' knowledge for clumping software together in ad-hoc ways.

We think it doesn't exist, because un-like StackOverflow with the long tail, no one has done a good job at making long form content social. This idea attacks AirPair's core mission head on. We'd love to have you apart of it too. So reach out to team@airpair.com and say hi!

<!--Our new Git powered Posts section is aimed to enable  collaboration on more consolidated, refined and clearly expressed long form technical content than ever before. We all experienced the transformation journey GitHub took us on by ushering in the era of Social Coding. Now we'd like to reuse what they built mixed with a little AirPair spice and build out community based around passion for sharing developer knowledge and learning from one another.-->


### 2.2 Improving ROI on content investment

`touch content-strategy.config`

We had great success in our first 6 months pushing community posts. The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficed post has been read more than 200,000 times and our 24 hour record is 35,000 vistors to a single post.

![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png)

The seeding phase was however, expensive and unsustainably heavy on internal manpower. To keep up the pace and quality encombent of our initial success, we needed to addres the following concerns.

**2.2.1 Crowdsource more of our content production workflow**

Every publisher dreams of ***user generated content***  magically appearing on their site. From experience, we can tell you, great content takes time and energy. Before this iteration, each post consumed almost 10 hours:

- Sourcing authors
- Considering proposals
- Editing, formating & QA
- Marketing & promotion

There is no shortcut, that time investment must come from somewhere. So we're hoping GitHub combined withour community review system will allow anyone to submit a post, the community to share the load and organically bubble the most popular posts to our attention.

**2.2.2 Reducing content half life**

As an author devoting personal energy, or publisher comissioning content, the main goal is for what you produce to stay relevant for as long as possible. We've covered how software moves exceptionally quick. The unfortunate ramification is Software content decays exeptional fast too.

Often the principals of a piece remain relevant, but as new framework versions emerge, it becomes unclear if the content is still useful.

Git provides a scalable way to accept maintenace updates. It even has the ablity to tag iterations of a post as relevant to specific framework versions.

### 2.3 Ways Git Enhances The Author's Experience

*** Sharing the load ***

Collaborating means fresh eyes to double-check your content and form. Editing a particuarly time and energy intensive procecess. The last 10% of changes usually require a disproportional amount of time and are the least fun. With an active reviewing community authors will save time editing and be able to focus more energy on the substance of their pieces.

*** Interaction as self improvement ***

The GitHub discussions and comments model around Pull Requests provide an amazing opportunity re-thinking and evolving subject matter thought, before reaching a publishable iteration. Even less advanced readers will force you to re-think how present concepts in clearer ways.

If you've always wanted to improve your writing, a portion of reiewers will be happy to help you express better grammar and style.

** 2.3.1 Adding collaboration to technical long form **

We've covered bits of this already. But

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
