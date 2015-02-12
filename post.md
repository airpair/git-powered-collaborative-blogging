--

> *** Our new GitHub powered authoring tools will be officially annouced first week of March. We'd love to have your feedback before then. Feel free to fork this post too. ***

<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

## 1 If GitHub & AirPair had a baby

`mkdir cat-brace-pencil-mutant`

No... neither this post or its title are intended to be provocative or taboo. If you haven't yet, I'd strongly recommend finding 15 minutes to watch *When Ideas Have Sex*. Besides being my favorite TED talk of all time, it's a great device to explain an idea we'd like to coin 'Social Authoring' as the mutantation of AirPair's Posts Section coming together with the GitHub API.

TODO *Insert funny pic of octocat-airpair illustration*

### 1.1 TLDR; annoucement

`touch Git-Powered-Collaborative-Developer-Writing.html` 

Today I'm excited to annouce one of the more innovative projects I've been involed with. Pretty much anything part git or Octocat related is going to be cool. If you've already enjoyed the AirPair posts section, it gives me great pleasure to let you know things are going to get way more interesting. From today, you are invited both as authors starting your own posts and reader contributing to posts by others, using our new *GitHub Powered Collaborative Workflow*.

![Collaborate on post using Git](/static/img/pages/posts/post-authoring-flow.png)

In this post, I'll intertwine many reasons why our new author setup is significant, while covering why we built it, how we put the the publishing flow together and what types of things we hope to see. 

Before deep diving into details, here's a screenshot and some use cases to get you thinking:

> ![Fork a post on AirPair](/static/img/pages/posts/fork-post-dymo.png)

- Annoyed with that typo? ***Fork and fix***. 
- Spot a syntax error? ***Fork and fix***. 
- Sample no longer runs with a new framework version? ***Fork and maintain***.
- Know a better way to do something? ***Fork and improve***.
- Disagree? ***Fork and discuss***.

### 1.2 In this post

`touch README.md`

**Section 1** covers a birds eye view of what we're doing. **Section 2** covers philophical and practical discussion on why developers need a git powered community blogging system. In **Section 3** I'll describe what our first implementation actually looks like, including the technicalities of how we put it together. In **Section 4** we'll get warm, soft and fuzzy with the  community building challenges ahead. Finally, **Section 5** will end with a summary leading into our [*$100,000 Writing Competition*](/100k-writing-competition).

### 1.3 What's in this for you?

`touch Why-write-on-AirPair.editorconfig`

Here's some pros we think you'll love. Each we'll explore in more depth, later in this post:  

**For readers**

- More comprehensive and up to date technical content than ever before.
- Clear quality signals from our review system that a post is worth reading.
- Ability to **contribute** small nuggets without the normal comprehensive understanding required to author a whole post.

**For authors** 

- Crowdsourced help improving your materpieces.
- Exposure to significantly more readers than publishing on your own.
- A forum to introduce, bounce and evolve new ideas before they become public.
- Instant recognition for great work, without aquiring prior developer fame.

### 1.4 How to get your hands dirty

`touch getting-started.man`

- [Starting a post](/post/new) is a piece of cake. 
- Forkable Posts have an orange 'Fork this post' button in the right rail. 
- The [Posts in community review](/posts/in-community-review) page shows posts waiting for feedback at any point in time.  

<!-- *TODO mention sharing and put share widget here* -->

### 1.5 From *Social Coding* to *'Social Authoring'*

`git commit "Developer Authoring Tools Intro" -m`

On behalf of the AirPair team, we hope you like what you've seen so far. You might consider using AirPair's bookmark feature if you'd like to return to this post later - it is a lengthy read. 

Our new Git powered authoring tools are aimed to enable wikipedia-like  collaboration for the purpose of working towards more consolidated, refined and clearly expressed long form technical content than ever before. We all experienced the transformation journey GitHub took us through by ushering in the era of Social Coding. Now we'd like to take advantages of what they built to experiment with a new 'Social Authoring' community passionate about sharing developer knowledge and learning from one another.

## 2 Why Build Git Powered Publishing?

`mkdir inspiration`

While writing this post, I keep thinking:

> *How cool would it be if everything on the web were forkable?* Imagine a digital world extinct of typos!

This section covers a gamut of different forces that led us to integrate the GitHub API with our existing author tools. Some of our motivations came from a sense that this could be groundbreaking and indeed evolutionary... Others guiding influences were simply marketing problems we needed to solve, probably challenges relevant to every publisher. Mostly though we've had a great time working with our authors. We thank you guys deeply for inpiring more than a million readers to come to AirPair in the last few months. We've been wating to make ways enhance your success and make it easier to find. To quote a friend who's tweet I came by in perfect timing writing this post:

![Make things easier](//airpair.github.io/img/2015/01/making-things-easier.png)

### 2.1 When Ideas Have Sex

`touch A-Sprinkle-of-TED-Magic.mov`

**2.1.1 Evolution as accelerating combinations of ideas**

One reason I started AirPair, was because it's an expression of many ideas presented in my all-time favorite TED Talk [When ideas have sex by Matt Ridley](http://www.ted.com/talks/matt_ridley_when_ideas_have_sex?language=en). Riley states his explanation for history progression in terms of the human ability to improve our living conditions and wealth: 

![Matt Ridley](//airpair.github.io/img/2015/01/matt-ridley.png)
> To answer that question, you need to understand how human beings bring together their brains, and enable their ideas to combine and re-combine, to meet and indeed to mate.

A part Ridely explores that is particuarly relevant to software, is the notion of acceleration. The more we interact, converse and exchange knowledge, the more our ideas combine and mutate forming products embodying of ideas originating from thousands or millions of indivduals. Interestingly, as ideas become more evolved, they are even more quickly supersceded. The Stone Axe was used for thousands of years, yet the mouse stayed relevant for only a few.

**2.1.2 GitHub => Social Coding**

`touch Ode-to-Octocat.git`

You're a developer, so you've see hands down what Rideley is talking about. Every year  the cycle of new frameworks appearing, spreading world-wide and before you know it, being supersceded becomes shorter. 

Software ideas having sex is old news, largely thanks to GitHub. By abstracting git, building great UI that removed friction for the common developer to setup and wield git and slapping an incrediible community on top, they are majorily reponsible for making open source mainstream and programmers more intellectually promiscous. Even though it's been a while, I'm still awed and thankful to those GitHubbers that first empowered developers, who had never met, to collaborate, contribute, discuss and form bonds while improving work.

*By deduction, it seems though we may have a challenge to solve. If we're going to make better software faster and faster, we'll need more efficient and powerful tools to express and share the ideas embedded in our software...*

** 2.1.3 AirPair => Social Authoring**

`touch git-powered-publishing-elevator-pitch.wav`

AirPair's is known primarily for connecting developers over video chat for one-on-one pair programming help. This is one expression of our broader mission - to find new ways to connect developers for the purpose of knowledge sharing and relationship building.

We think the developer world could use a Wikipedia like collection of quickstarts, tutorials and thought pieces and this ideas fundamentally expresses our mission. If these ideas are important to you too, I'd encourage you to reach about joining our team.

### 2.2 Improving ROI on content investment

`touch content-strategy.config`

We had great success in our first 6 months pushing community written technical content.

![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png)

The seeding phase was however, expensive and unsustainably heavy on internal manpower. To keep up the pace and quality encombent of our initial success, we needed to addres the following are some concerns.

**2.2.1 Outsource more parts the content production workflow**

Until now, we internally spent almost 10 hours on each post

- Sourcing an author
- Took submissions for topics
- Often guided the author to refined or better researched topic
- Edited and formatted from an author first draft
- QA / Publishing
- Marketing
- Finally incorporated fixes requested via email.

Sure, a lot of these sound like straight forward missing features, but not solving these problems the way they've been solved before allowed us to think from a different angle. We realized git could do a way better job than anything we would custom build. With a layer of a AirPair community driven quality control (covered in Section 3), now:

- Anyone can submit a post, but to be published the community has to approve
- We have a much tighter in-browser editing experience, so no more internal formatting / editing.
- Anyone can fork and help an author fix things or make a posts better
- Post can be self published by an Author, once the community says it's good to go
- We can easily track high post quality, so know when we should market already popular work
- Forking will allow readers and authors to undergo post published revision work without internal support.

Damn... I'm excited to get back to coding airpair.com! 

**2.2.2 Reducing content half life**

<!--When a developer writes an amazing piece, often the specific, syntax, interfaces will be out of date well before the principals become irrelevant.

A git powered platform will enable content to morph with external shifts in framework releases, vulnerability discoveries and other evolutions of software thought.-->

As an author devoting personal enegery, or a publisher comissioning content, you want what you create to stay fresh and relevant for as long as possible. We've covered how software moves exceptionally quick. This has an unfortunate ramification on software publishing. Software content decays exeptional fast too. This may explain why there is a universal *long tai* content network - StackOverflow, and lots of independed *short tail* content providers, open-source contributors and companies that product their own technology, but no universal medium-tail wiki of how to pieces for software.

An additional frustrating for both Author and Reader, is when the principals and structures of a piece remain relevant, but a new framework versions emerges, making a piece harder to extract immediately value from, or even though well respected, unclear to the reader if still relevant. I'll never forget starting BackboneJS and wondering if the tutorials google suggested were written for the same framework I wanted to use.

Wouldn't it be nice if there were a scalable way to know (1) when a post needs an update, (2) an easy way to mainain it, (3) even a way to tag it relevant to specific framewor versions?

Git solves all of these challenges so nicely. Soliciting the community to fork helps us know when we need to update things. Forking & merging reduces friction to recieve and incorporate fixes. At some point in the future, we hope to look at tagging as a way to know and browse different versions of a post relevant to the framework versions you are using.

If you are a company maintaining your own API docs and how to guides. I'd invite you to reach out and experiment with us. AirPair could be an incredible place to improve your content quality, reduce production and maintenance cost and win new community. We'd love not only how to guides, but also cover feature releases and in the wild success stories from which others can learn.

** 2.2.3 Motivating more authors and content **

Our goal, for each author on AirPair is to maximise:

- a. Reconition
- b. Interaction
- c. Self-improvement
- d. (monetary) Prosperity 

We got off to an awesome start in 2014. We birthed a few new stars, generated significant traffic, taught our experts how to write succesful posts and paid them well :).

The average post published on AirPair in January 2015 received more than 15,000 views. Our most trafficed post has been read more than 200,000 times and our 24 hour record is 35,000 vistors to a single post.

We think 'Social Authoring' is a path to making these successes of our authors so far, the appetizer, before the main course.

*** Recursively growing audience ***

More authors leads to more readers which in turn attracts more readers. We're better Social Authoring will be a more interactive and enjoyable process leading to better work, worthy of more recognition from greater number of eye balls. If you have more ideas on how we can make AirPair your go-to scratch pad, let us know!

<!--*** Forming sub-communities by connecting you on interests ***

With your contributors acknowledged and listed on your published work, we hope over time to foster recuring bonds. People you become familiar with for having your back, also happy to help with a tweet or share to let the world know your shared work is ready. Many you might realize that you have their back and enjoy bouncing their ideas back when it's their turn.

This already happens over the internet and twitter for veteran personalities and bloggers. We think, we can lower the bar for the masses.

 But to start, let me explain the white space in between the extreme long tail *Stackoverflow* sparked our imaginations, when everyone realized how neccessarily a consolidated resources of extreme long tail knowledge was. On the other end of the spectrum, PluralSight, -->

*** Self improvement on subject matter & style ***

Teaching itself is a form of learning. When you write a post you are already re-arranging and improving knowledge structures around what you are expressing. But when you let your ideas have sex, even with people less advanced than you, they still force you re-think how to present it, so that it becomes easier to consume. You'll also be exposed to other teacher level peers who will challenge and help re-inforce your arguments.

If you've always wanted to improve your writing, a portion of readers will help you express better grammar and style. I'm personally excited for this.

*** Overnight exposure and demand ***

"It was great to get some exposure. The process was very straightforward. I learned a lot by having to write and present on the topic and I received many inquiries following the article" - [Mark Meyer (150k readers)](https://www.airpair.com/angularjs/posts/top-10-mistakes-angularjs-developers-make)

![Mark Mayer](https://0.gravatar.com/avatar/6c2f0695e0ca4445a223ce325c7fb970?s=80)

### 2.3 Ways Git Makes The Author's Experience Better

** 2.3.1 Adding collaboration to technical long form **

We've covered bits of this already. But collaborating means fresh eyes to double check content and form. Editing is one of the most time and energy intensive procecesses neccessarily to reach professional standards. The last 10% of changes, usually require a disproportional amount of time and are the often the least fun. We'd like to execute a flow where you barely have to exhert yourself in this part of the process and instead rely on the community - so you can focus on the content itself.

** 2.3.3 Reducing author maintenace responsibility **


** 2.3.4 Helping you take more credit **

<!-- As a reader you will get smarter, as you will be exposed to better content improved through crowdsourced spelling and grammer improvements, pre-vetted ideas and statements, and lower bar to partcipate and contribute with resulting self improvement by engaging and only bits and pieces of a collaboratively created post that belong mostly to an author and also partially to it's contributors. If you don't want anyone to make suggestions on what you write, this might not be for you.

As an author you will make better work and be help, plus challenged to improve what you present. If you're so interested in a topic that you are going to spend hours or days sharing it, it's a no brainer to be given people passionate about what you've got to say that you don't have to find by maintaining a consistant blog that already made you famous. Ods are, if you post something on your own blog, many people will spot and think the same improvements, but you never become a aware of many of them because it's too hard for them to get what they see in their head onto your published piece. We hope we can help you engage that percentage of your readers.
 
Yes, people have published and translated books on github. Git is almost every developers favorite tool... but it was Github who took the tool and combined beautiful product and execeptional community building to make something, somewhere in-between technology and common conciousness, to bring about the next level of cognitive collaboration. Wow, the day I understood that you could work with someone without having met them, or even know thei name - I knew Github was my favorite startup. -->

## 3 How and what we built

### 3.1 AirPair's live editor

TODO screenshots and short explanation of the editor.

### 3.2 Our 3 Step Publishing Flow

This is our first go at gluing the GitHub API and AirPair authoring tools together, so there's probably gaps and a way to go for it to become optimal, but here it is.

** V1 of The workflow **

The goal of V1 was to make it work with as little development on AirPair sided features as possible. We wanted to leverage as much of the existing GitHub API and github.com UI and tooling as possible because:

1) Despite what you may perceive, AirPair is a tiny company.
2) Git and GitHub are already perfect for enabling history, discussions around sugested changes, facilitating submissions and accepting / rejecting changes.
3) There's no way we could rebuild it as well as GitHub.
4) We wanted to leverage existing Developer familiarity with github and their own personal toolset that already know and love. As a contributor, once you fork a post you have the option of doing nothing futher on airpair.com if you prefer to work exclusively in your own environment.

At the end of the day, we mainly thought AirPair's contributions would be leveraging its large traffic base and existing community to pose this idea to enough influencers for things to spark. We'll attempt to categorize and present content to readers in a more and sophisticated way as things progress, but ultimately - we'll let you in on a secret.

95% of airpair.com was built by one coder. One additional developer contributed to this particular part of the site and the total time to knock all this out was probably between 6-8 weeks. Not a very defensible technolgoy play, especially that I'm about to tell you everything anyway!

*** The workflow ***

Posts basically go through 3 states:

> Draft => In Community Review => Published

#### Draft

`touch Fun-and-games.md`

When you create a new post, it stats in ***Draft***. While in draft your post is only visible to you. It has no git history, so there's no pressure about playing with an expressing ideas that not yet make cohesive sense. We simply save your changes back to our database with no history and if you start and it never goes anywhere, that experience was just for you, so enjoy it and don't worry about taking it seriously until you realize you want to.

When you post meets some very basic critera, like being longer than a certain number of words, tagged with the relevant technolgoies and you've supplied an image to be used as a thumnail on airpair.com and social media you can submit it to the community for review. 

Once you've got those bits in, you can do a full preview of the post to feel what it's going to look like if it were published.

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

### 3.3 How we peiced it together

#### Our stack

#### The AirPair Editor

** marked & ace in tandem **

Performance & Debouncing

** github-node npm package and our fork ** 

API calls


## 4. The people side

`mkdir where-to-from-here`

We're excited to make this work, but community is only part technology. That's one of the things we care about at AirPair, all the nodes and connections that make up real thriving community. We hope that this becomes another way the developer world makes not only the evolution of knowledge, but experiences each other on a personal level for plain old simple human connection.

### 4.1 Community Building from Grass Roots



### 4.2 Partnering with Technology and API providers

## 5. Conclusion

We hope this project is as impactful as we think it can be and that news of these tools spread through the developer world. At AirPair we come to work each day focused on how we can make a company thrive around enabling knowledge transfer from developer to another. We hope to see your posts and contributions. Thanks for stopping by.
