--

> *** Our new authoring tools will be officially annouced first week of March. We'd love to have your feedback before then. Feel free to fork this post too. ***

<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1. If GitHub & AirPair had a baby

`mkdir cat-brace-pencil-mutant`

TODO *Insert funny pic of octocat with airpair brace and pencil*

### 1.1 TLDR; annoucement

`touch Git Powered Collaborative Developer Blogging` 

Today I'm excited to annouce one of the more innovative projects I've been involed with. Pretty much anything part git or Octocat related is going to be cool. If you've already enjoyed the AirPair blog, it gives me great pleasure to let you know things are going to get way more interesting for here. From today, you are invited both as an author and reader to become a contributor to our community blog using our new *Github Powered Collaborative Workflow*.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

In this post, I'll intertwine many reasons why our new setup is significant, while covering why we built them, how we put the the publishing flow together and what types of things we hope to see. 

Before diving into detail, perhaps a good chunk of the value can be summed up by this screenshot and a few uses cases:

> ![Fork a post on AirPair](/static/img/pages/posts/fork-post-dymo.png)

- Annoyed with that typo? ***Fork and fix***. 
- Spot a syntax error? ***Fork and fix***. 
- Sample no longer runs with a new framework version? ***Fork and maintain***.
- Know a better way to do something? ***Fork and improve***.
- Disagree? ***Fork and discuss***.

### 1.2 In this post

`touch README.md`

**Section 1** covers a birds eye view of our what we're doing. **Section 2** covers philophical and practical discussion on why developers need a git powered blogging system. In **Section 3** I'll describe what our first interpretation actually looks like and the technicalities of how we put it together. In **Section 4** we'll get all fuzzy with the soft community building challenges ahead to make it work. Finally, **Section 5** will end with a summary and lead into our *$100,000 Writing Competition*.

### 1.3 What's in this for you?

`touch Why write on AirPair`

Here's a list of pros we think you're going to love. We'll explore each more depth in later parts of this post:  

**For readers**

- More comprehensive and up to date technical content than ever before.
- Clear signals from our review system that a post is worth reading.
- Ability to **contribute** small nuggets of knowlege without the comprehensive understanding of a subject matter required to author your own post.

**For authors** 

- Crowdsourced help improving your materpieces.
- Exposure to significantly more readers than publishing on your own.
- A forum to introduce, bounce and evolve new ideas before they become public.
- Instant recognition for great work, without aquiring prior developer fame.

### 1.4 How to get your hands dirty

`touch Getting started`

- [Starting your own post](/post/new) is a piece of cake. 
- Posts with GitHub repos will already have the orange fork button in the right rail. 
- Visit [Posts in community review](/posts/in-community-review) anytime you to see posts waiting for feedback.  

<!-- *TODO mention sharing and put share widget here* -->

### 1.5 Intro Summary

`git commit "Developer Blogging Tools Intro" -m`

Summing up before we deep dive, we look forward to enabling wikipedia-style developer collaboration for the purpose of creating more refined, perfected and clearly expressed long form technical content. We think Git and the GitHub API provide the perfect, powerful and familiar opportunity tools to make it so. To find out why, read on.


## 2. Why Build Git Powered Publishing?

`mkdir inspiration`

While writing this post, I keep thinking:

> *How cool would it be if everything on the web were forkable? Imagine a digital world extinct of typos!*

This section covers a gamut of different forces that led us here. Some of our motivations came from a sense that this could be groundbreaking and for the glory of evolution! Others were marketing problems we needed to solve, probably relevant to every publisher. Mostly, through the experieces of working with our past authors, we just had to make their success greater and experience better.

### 2.1 When Ideas Have Sex

`touch A Sprinkle of TED Magic`

#### 2.1.1 Evolution as accelerating combinations of ideas

One reason I started AirPair, was because it was an expression of many ideas presented in my all-time favorite TED Talk [When ideas have sex by Matt Ridley](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en). Riley states his explanation for the human ability to improve our living conditions and wealth as history progresses: 

> To answer that question, you need to understand how human beings bring together their brains, and enable their ideas to combine and re-combine, to meet and indeed to mate.

A part of this phenomenon that is particuarly relevant to software, is the notion of acceleration. The more we interact, converse and share knowledge, the more our ideas combine and mutate forming knowlege and products composed of ideas originating from thousands or millions of indivduals. But as ideas become more evolved, they are even more quickly supersceded.

#### 2.1.2 GitHub & *Social Coding* enabling promiscuous Open Source

`touch Ode to Octocat`

You're a developer, so yes you get what I'm talking about. We see every year the cycle of new frameworks appearing, spreading world-wide and before you know it, being supersceded by new kid on the block. 

Ideas having sex is old news in software creation largely thanks to GitHub for reducing the friction for the common developer to setup and wield the powers of git. Even though it's been a while, it's still awing to think about how GitHub empowers developers, who have never met, to collaborate and improve work.

It seems though, if we're going make better software faster and faster, we could use more powerful tools to speed up the job of expressing and sharing the ideas embedded in our software?

#### 2.1.3 AirPair & *Social Code Blogging* enabling promiscuous knowledge share

`touch The git powered publishing elevator pitch`

AirPair's is known primarily for connecting developers over video chat for one-on-one pair programming help. But, this is one expression of our mission to find new ways to connect developers for the purpose of knowledge share.

With your support, we'd like a shot at championioning the idea of ***'Social Code Blogging'***. We think the developer world could use a wikipedia like collection of quickstarts, tutorials and thought pieces across all technologies and framework versions.

### 2.2 Improving ROI on our content investment

`touch Content strategy`

We had great success in our first 6 months pushing community produced technical content.

![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png)

But the seeding phase was expensive and unsustainably heavy on internal manpower. The following are some concerns we needed to address to keep up the pace and quality encombent of our initial success.

#### 2.2.1 Making content production more self sustaining

-- 

#### 2.2.2 Reducing content half life

As an author devoting personal blood, sweat and tears, or a party  comissioning content, you want to see what you create stay fresh and relevant for as long as possible.

Software moves so quickly that if you've been out of the game for 18 months, you might not have current experience in demand. Similarly, what was published 18 months ago, if not completley irrelevant, most likely will not work or be sub-optimal with newer framework versions and features.

Wouldn't it be nice if there were a scalable way to know when a post needs an update and a way to update it?

#### 2.2.3 Reducing editorical cost per post

We spent exhaberant amounts of time and money for each post published in 2014. Money that could only come from a venture funded Startup. But our team is small and resources not unlimited. So it's been a huge focus to reduce the time we spend identifying what to write and time editing for it to reach the standards we produced over the last 6 months. 

With our new tools, we hope to crowdsource quality control before AirPair staff get invovled. Our review system is one piece not powered by github, that goes hand in hand with the github bits that faciliate the work that is discovered during the review process for an article to meet community standards.

### 2.2.4 Motivating more authors and content

At the end of the day, if an author shares something with the public, the ultimate goal is having it be read for (a) reconition, (b) interaction, (c) improvement (d) prosperity. We got off to an awesome start last year, generating significant traffic by seeding out posts section through well paid contributions and excellent covereage. The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficed post so far has been read more than 200,000 times and 24 hour record is 35,000 vistors.

We believe the ideas presented here around 'Social Code Blogging' will be a way to make last years success for authors the appetizer, before the main course. (*for Americans :)

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

 But to start, let me explain the white space in between the extreme long tail *Stackoverflow* sparked our imaginations, when everyone realized how neccessarily a consolidated resources of extreme long tail knowledge was. On the other end of the spectrum, PluralSight, 

### 2.3 Ways Git Makes Technical blogging better

#### 2.3,2 Introducing collaboration to technical long form content

We've seen collaborative content revolutionize and destroy the encyclopedia industry. Thus, publishing technical content has less return than other subject matter. I wonder if this explains why there is no universal technical blogging platform, when there is a universal technical Q & A platform - StackOverflow - which supplies by far the majority of long tail knowledge for the developer world. Is it the way they captured community and empowered it to socially collaborate? I'm suprised this didn't happen in a big way yet anywhere for the blog post / tutorial format. It seems obvious, so I'm glad we're here having a crack.

#### 2.3.2 Improving maintainbility

When a developer writes an amazing piece, often the specific, syntax, interfaces will be out of date well before the principals become irrelevant.

A git powered platform will enable content to morph with external shifts in framework releases, vulnerability discoveries and other evolutions of software thought.

Who knows, one day we might go as far as implement some sort of tagging and branching so that you can even view releases of a post if you have to go back and do some maintenance. Until then, you could follow all the commit logs and even discussions on pull requests submitted to each post on AirPair to get what communal interaction led to something being preseted how it was, just like any other opensource software made by collaborating developers.

As a reader you will get smarter, as you will be exposed to better content improved through crowdsourced spelling and grammer improvements, pre-vetted ideas and statements, and lower bar to partcipate and contribute with resulting self improvement by engaging and only bits and pieces of a collaboratively created post that belong mostly to an author and also partially to it's contributors. If you don't want anyone to make suggestions on what you write, this might not be for you.

As an author you will make better work and be help, plus challenged to improve what you present. If you're so interested in a topic that you are going to spend hours or days sharing it, it's a no brainer to be given people passionate about what you've got to say that you don't have to find by maintaining a consistant blog that already made you famous. Ods are, if you post something on your own blog, many people will spot and think the same improvements, but you never become a aware of many of them because it's too hard for them to get what they see in their head onto your published piece. We hope we can help you engage that percentage of your readers.
 


Yes, people have published and translated books on github. Git is almost every developers favorite tool... but it was Github who took the tool and combined beautiful product and execeptional community building to make something, somewhere in-between technology and common conciousness, to bring about the next level of cognitive collaboration. Wow, the day I understood that you could work with someone without having met them, or even know thei name - I knew Github was my favorite startup.

## 3. How and what we built

### The live editor

TODO screenshots and short explanation of the editor.

### Our Publishing Flow

This is our first go at gluing the GitHub API and AirPair authoring tools together, so there's probably gaps and a way to go for it to become optimal, but here it is.

### V1 of The workflow

#### Staying as lean as possible

The goal of V1 was to make it work with as little development on AirPair sided features as possible. We wanted to leverage as much of the existing GitHub API and github.com UI and tooling as possible because:

1) Despite what you may perceive, AirPair is a tiny company.
2) Git and GitHub are already perfect for enabling history, discussions around sugested changes, facilitating submissions and accepting / rejecting changes.
3) There's no way we could rebuild it as well as GitHub.
4) We wanted to leverage existing Developer familiarity with github and their own personal toolset that already know and love. As a contributor, once you fork a post you have the option of doing nothing futher on airpair.com if you prefer to work exclusively in your own environment.

At the end of the day, we mainly thought AirPair's contributions would be leveraging its large traffic base and existing community to pose this idea to enough influencers for things to spark. We'll attempt to categorize and present content to readers in a more and sophisticated way as things progress, but ultimately - we'll let you in on a secret.

95% of airpair.com was built by one coder. One additional developer contributed to this particular part of the site and the total time to knock all this out was probably between 6-8 weeks. Not a very defensible technolgoy play, especially that I'm about to tell you everything anyway!

#### The workflow

Posts basically go through 3 states:

> Draft => In Community Review => Published

##### Draft

###### Fun and games

When you create a new post, it stats in ***Draft***. While in draft your post is only visible to you. It has no git history, so there's no pressure about playing with an expressing ideas that not yet make cohesive sense. We simply save your changes back to our database with no history and if you start and it never goes anywhere, that experience was just for you, so enjoy it and don't worry about taking it seriously until you realize you want to.

When you post meets some very basic critera, like being longer than a certain number of words, tagged with the relevant technolgoies and you've supplied an image to be used as a thumnail on airpair.com and social media you can submit it to the community for review. 

Once you've got those bits in, you can do a full preview of the post to feel what it's going to look like if it were published.

###### No turning back

As you go to submit your post, you will be prompted to authenticate with GitHub repo privilages. This is because this is the moment when things get real. We take the repo name you provide (which you cannot change later) and spin up a private repository on the github.com/airpair org. Repo permissions allow us to add you to "The Author" team on your repository. Thus, besides god users in the airpair org, you are the only one with write access to accept and merge or reject pull requests coming in for your contributors forks.

As discussed in the next state, the rules of the game change when you hit, so pay attention, it's worth understanding how things work before you push that button!

###### Properties of the *draft* state

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

##### In Community Review

###### Where your content lives and gets saved

Once your post is submitted, you have to choice to continue editing on AirPair, or clone your repo and use your normal tools. Either way each time you save your post including from the editor it gets committed to master on github. The markdown appearing in the edidot actually comes from HEAD on github and will not appear on airpair.com until you hit ***Propagate HEAD***. 

###### Visibility

Congrats, your post is now visible to anyone logged in to AirPair. You meant to do that right? Well relax, it's makred as noindex, follow so only hardcore contributors that want to take the time to be invovled in unfinished work will look at it. It also won't get imortalized in google's memeory until it's published. 

###### Properties of the *review* state

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

##### Published

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

#### What we used to put this together

##### Our stack

##### The AirPair Editor Experience

###### marked & ace in tandem

####### Performance & Debouncing

##### github-node npm package and our fork

###### API calls




## 4. `mkdir` where-to-from-here ?

We're excited to make this work, but community is only part technology. That's one of the things we care about at AirPair, all the nodes and connections that make up real thriving community. We hope that this becomes another way the developer world makes not only the evolution of knowledge, but experiences each other on a personal level for plain old simple human connection.

### Building a Blogging Community



### Partnering with Technology and API providers

## 5. `mkdir` conclusion

We hope this project is as impactful as we think it can be and that news of these tools spread through the developer world. At AirPair we come to work each day focused on how we can make a company thrive around enabling knowledge transfer from developer to another. We hope to see your posts and contributions. Thanks for stopping by.
