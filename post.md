<!-- *TODO add CTA to subscribe to the AP Content Maillist here.* -->

> **tldr;** Would writing technical content get easier if we collaborated using
the same git flow for content as we do for code? Fork this post and join the *Mother Forkers Developer Content Revolution*!

## 1 Filling a gap with Social Authoring

Thanks to StackOverflow's *Social Q&A* platform, we have a reliable,
universal go-to for *long tail* software knowledge. "Long tail" meaning niche
topics that need to be found using lots of words like "Ace Editor onChange
event rendering performance with AngularJS". On the *short* end of the
spectrum, docs by Open Source creators and API companies provide excellent
answers for most queries like "AngularJS Directive". But what about questions
in between, like "How to scale a mobile chat system with Firebase?" or "Should
I use BackboneJS or EmberJS?".

Independent posts scattered across the web are our best tools when searching
for *medium tail* answers. However, unless you recognize an author, its hard to
know if you're about to read the best or even a good post on a given subject.
From the publishing perspective, ***writing high quality long form technical
content is hard*** and often even harder to maintain. Yet more frameworks are
appearing faster and faster each year and with it comes *** a challenge to
cover permutations of using different technologies together to solve real world
problems ***. 

The Social thing worked for Q&A on StackOverflow. It also worked for coding on
GitHub. It even worked for long form encyclopedia content. Can we step-up
developer authoring and create better technical content, more efficiently than
ever before with some sort of StackOverflow-GitHub-Wikipedia hybrid social
magic?

### 1.1 Announcing Social Authoring on AirPair

Pretty much anything part Git, or Octocat related is going to be cool. If
you've already enjoyed some of the epic community posts that have gone
viral on  AirPair, it gives me great pleasure knowing from today our
community content is  about to get way more awesome, because ***authors can
now work with readers using Forks and Pull Requests***.

With our new *GitHub Powered Workflow*, we hope to usher collaboration
that will enable more accurate and refined technical writing.

![Collaborate on post using
Git](/static/img/pages/posts/authoring-flow.png)

In this post, I'll cover how we integrated GitHub and many cool 
opportunities that make our new authoring setup significant. We'll end
leading into our ***$100,000 Developer Writing Competition***. 

Before diving into details, here's a screenshot to get you thinking:

![Fork a post on
AirPair](//airpair.github.io/img/2015/01/fork-examples.png)

### 1.2 Benefits of Social Authoring

**For readers**

- More proofed, comprehensive and up to date technical content than ever
before 
- Clear quality signals with what posts are worth reading
- The **ability to contribute** small bytes, without the level of understanding
required to author an entire post

**For authors**

- Exposure to more feedback than publishing elsewhere
- Crowdsourced help with improving post quality
- A forum to bounce new ideas before they become public
- Instant exposure for great work (with or without a social
following)

### 1.3 Getting involved

- **[Starting a post](/posts/new)** is a piece of cake. Everything is
private until you submit to the community 
>[![Start a
post](//airpair.github.io/img/2015/02/start-post.png)](/posts/new)

- Hit the *fork* button in the right rail to start contributing to someone else's post
>[![Review a
post](//airpair.github.io/img/2015/02/fork-button.png)](#review)

- Give feedback with the review widget at the bottom of each post
>[![Review a
post](//airpair.github.io/img/2015/02/review-post.png)](#review)

- Help community vet and Q/A **[posts in review](/posts/in-community-review)**
waiting to get published

- Bookmark this post if you want to come back to it later

## 2 Why we built publishing on Git

If you're more interested in the technicalities on what and how we built
things, you might want to jump to <a href="#3-1-a-3-step-authoring-workflow">section 3</a>.

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


One part of the talk that is particularly relevant to software, is the notion
of our ***intellectual acceleration***. The more we interact, converse and
exchange knowledge, the more our ideas combine and mutate forming new ideas and
products. Things you and I conceive day-to-day as single ideas, actually embody
previous ideas originating from thousands or even millions of individuals.

> ![Stone
Axe](//airpair.github.io/img/2015/02/matt-ridley-stone-axe.jpg) 

Interestingly, as ideas become more evolved, they are even more quickly
superseded. The Stone Axe was used for thirty thousand years, yet iPhones are
now out of fashion within a few months.

> ![Mouse](//airpair.github.io/img/2015/02/matt-ridley-computer-mouse.jpg) 

** 2.1.1 (Developer) Intellectual Acceleration **

As developers, we've seen hands down what Ridley is talking about. Every year
the cycle of new frameworks appearing, spreading worldwide and becoming second
best, gets shorter. Largely thanks to GitHub making Open Source mainstream,
*Developer ideas having sex* is old news. 

AirPair's thesis for existing, is based on an observation: *As we make better
software faster and faster, we'll need more efficient and powerful ways to
express, share and consume the knowledge embedded in our code.*

** 2.1.2 Socially creating better content faster **

We're primarily known for connecting developers over
video chat for live one-on-one help. But our broader mission is to find new
ways to create relationships between developers that enable more efficient
knowledge share. 

So with our mission in mind, we'd love you to join our experiment
to see if we can reproduce what StackOverflow did for Q/A starting a
Wikipedia-like community using the same tools GitHub used to usher in the era
of Social Coding.

<!--** todo insert illustration ** 

### 2.2 How Git Improves ROI on Content Marketing

We had great success in our first 6 months pushing community content. The
average post published on AirPair in January 2015 received more than 15,000
views. Our 24 hour record is 35,000 reads and the most trafficked post has been
visited 250,000+ times. 

> ![AirPair Traffic Growth](/static/img/pages/postscomp/traffic-growth.png) 

The seeding phase was however, expensive and unsustainably heavy on internal
manpower. To keep up the quality and pace incumbent of our initial success, we
needed to decrease the effort of finding authors, reduce the time our internal
team assited with editing. 

Every publisher dreams of ***user generated content*** magically
appearing. From experience, we can tell you, great content takes time and
energy. During our seed phase, each post consumed around 10 hours of internal
manpower. There's no shortcut, so we've built a crowdsourcing review and rating
system to crowdsource vetting and Q/A before our internal team gets involved.
-->
> ![Crowdsourced Editng](//airpair.github.io/img/2015/02/post-rating-signal.png)

A great side effect is that stars immediately indicate to readers as the browse, which posts to pay attention to. 

<!-- insert contributors screenshot here -->

### 2.2 What Git offers to the Authoring Experience

** 2.2.1 Sharing editorial load with Pull Requests ** 

Editing is a particularly time and energy intensive step in publishing. The last 10% of changes usually require a disproportionate amount of time and are the least fun... The same Git flow you know and love for code review can enable fresh eyes that have spotted fixes to send them to you.

> ![Crowdsourced Editing](//airpair.github.io/img/2015/02/crowdsourced-post-editing.png)

**2.2.2 Extend content life time and relevance** 

We've covered how software moves exceptionally quick. The unfortunate byproduct
is, software content decays exceptionally fast too. Often the principals of a
piece remain relevant, but as new framework versions emerge, it becomes unclear
if the content is still useful. Maintaining content against moving code bases
has never really been possible as an individual and is an unwieldy endeavour
for companies. Git provides a way to collaboratively maintain posts through
forks and pull requests. It can even be used to tag and retrieve iterations
relevant to specific framework versions.

** 2.2.3 Discussing evolving ideas with GitHub Comments ** 

GitHub issues, discussions and comments provide an amazing opportunity to get
feedback that will force you to re-think the subject matter. Influencers
will help you reinforce your arguments and less advanced readers will force you to simplify and present concepts in clearer ways. 

## 3 What we built

### 3.1 A 3-Step Authoring Workflow 

All posts go through 3 phases. Authors, Contributors and Editors have varying visibility and functions at each stage:

![3 Step Authoring Workflow](//www.airpair.com/static/img/pages/posts/social-authoring.png)

### 3.2 Leveraging GitHub as much as possible 

We wanted to use as much existing functionality provided by GitHub's API and github.com as we could. Not only does GitHub already have rock solid discussion
capabilities, merge tools and such that we didn't want to rewrite, Developers are already familiar with and love their tooling.  

Theoretically, once a contributor forks a post, they can work exclusively on github.com or from their own environment to send suggested edits back to the author. The AirPair editor does hide some complexities though.

### 3.3 Editing, previewing and storing posts

** 3.3.1 Posts in `DRAFT` **

Authoring starts in our live editor. Posts are written in markdown via Cloud 9's [ace web IDE](http://ace.c9.io/). Next to the editor we periodically preview how the body of your post would render using the [marked library](https://github.com/chjj/marked"). 

> ![AirPair Live Editor](//airpair.github.io/img/2015/02/edit-post.png)

In DRAFT, things are simple. A single version of your markdown is stored in our
database without any versioning or edit history. We wanted authors to be as
comfortable as possible splatting whatever comes out of your head with no
consequence or papertrail. When you click the PREVIEW button to see a full page
preview your post, you will see the same copy of your draft markdown stored in
our db.

** 3.3.2 Post in `COMMUNITY REVIEW` **

When a post is submitted to the community for review, a *master* open source
repo is created on [AirPair's GitHub organization account](//www.github.com/airpair) so that authors can begin to receive pull
requests with suggested improvements. All edit history from this point is
tracked by git and can be explored by anyone on GitHub.com same as any other
open source code base.

>  ![AirPair Live Editor](//airpair.github.io/img/2015/02/my-contributions.png)

To give authors permissions to edit and accept pull requests to the master
repository we create an `organization team` exclusively for a post's repo
adding only the author with write privileges.

A post's markdown is stored in a `post.md` on a branch called "Edit". Using a
branch stops the post.md getting indexed by Google. You're welcome to make
edits to your post from any environment you like, but you will need to stay on
the `edit` branch.

*** From the author point of view ***,
when authors edit from the AirPair editor, they are editing HEAD on the `edit`
branch from the master repository. The preview feature reads this same file.
The version displayed to reviewers comes from a completely different source,
the same placeholder in our database that previously stored the posts' markdown
file in draft. This has two nice side effects. (1) We don't have to make round
trips to GitHub when showing a post to other users. (2) Authors can make
changes and preview them without affecting the live version displayed to reviewers.

When the editor says your posts is `unsynced`, it means there is a newer
version in Git than being shown to others. Authors can SYNC changes from HEAD
to the version in our database whenever they like. 

***From a contributors point of view***, when a contributor edits from the
AirPair editor, they are editing HEAD on the `edit branch from THEIR FORKED
repository. The preview feature reads this same file (on their fork). This is
super cool, as an author can edit master and preview their changes as the same
time a contributor makes and previews their own. All of this happens while the
version other reviewers are seeing continues to be served and intact from our
database.

***All pull request and merging*** activity happens on GitHub.com via pull
requests from the `edit` branch of a fork to the `edit` branch of the master
repo on AirPair's org account.

** 3.3.3 `PUBLISHED` Posts **

`PUBLISHED` posts take advantage of all the same forking and merging
goodness as posts in `COMMUNITY REVIEW`. Everything is stored in all the same
places. Contributors can continue to fork. Authors can continue to edit. The
only exception is that a user much have AirPair `editor` privileges to `sync`
HEAD to the published version of a post.  

### 3.4 Visibility, Ratings & Publishing

** 3.4.1 Posts in DRAFT **

Post in draft are visible only to the author. They are not surfaced anywhere
around the airpair.com website. As such they cannot be reviewed or given
ratings. No repo exists, so no forking and merge activity is possible.


** 3.4.2 Posts in COMMUNITY REVIEW **

In review, posts are semi-private, in the sense that they are not shown in our
main [posts section](//airpair.com/posts) and are not indexable by Google.
Users can only access posts if logged in. And all posts in review can be found
on the [posts section](//airpair.com/posts/in-community-review) In Community
review page. This is to allow an author to present unfinished work without
permanent consequences.

Even reviews given by other users can be updated at anytime, so don't worry if
someone gives you criticism. All you have to do is convince them through
improving your work to take it down and replace their comment with a more
positive one.

A post in review can be published by its author once it has 3 reviews with a
3.5/5 start rating or higher.

** 3.4.2 PUBLISHED Posts **

Published posts are visible by anyone, whether logged in, anonymous or actually
a computer. Users will need an AirPair account to fork posts and leave reviews,
though they will be able to read reviews by others without being logged in.

## 4 Conclusion

We hope this project is as impactful as we think it can be. At AirPair we come
to work each day focused on how we enable knowledge transfer from one developer
to another. We hope to see your posts and contributions. If you haven't yet,
now is a great time to check out our $100k Writing Competition.

[![$100k Developer Writing
Competition](//www.airpair.com/static/img/pages/postscomp/og.png)](http://airpair.com/100k-writing-competition)