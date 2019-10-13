# What is Git?
Git is a tool for "version control" (alt. "revision control", "versioning"). It is not the only tool for version control; Mercurial is another modern example.

## What is "version control?"
We've all had this happen before. Researchers do this file naming thing. All. The. Time.

<img src="/images/phd101212s.gif" width="450">

[Comic by Jorge Cham](http://phdcomics.com/comics/archive.php?comicid=1531)

We do it so we can track the changes we make, collaborate with other researchers, and revisit old versions of our files. But there's a better way! (Hint: we suggest using git!)

So let's set down some functional requirements for version control needed by researchers.

------------------------------------------------------------------------------------------------------------------------------
## Functional requirements of version control for researchers

1. Make it possible to *track changes* to documents, code, data, etc. *over time*
2. Make it possible to *organize those changes* in meaningful ways
3. Make it possible to *publish*, *collaborate*, and *share* your work

### 1. Make it possible to track changes
- Keep track of past versions of files
- Keep track of which changes were made to which versions of files
- Keep track of who made which changes and when

### 2. Make it possible to organize changes
- Group related changes, even if they happen at different points in time
- Associate changes with tags or messages that make sense to you and others

### 3. Make it possible to publish, collaborate, and share
- Publish code and/or data alongside your papers
- Collaborate with others in real time
- Share your work with the *entire* world so others can use it, build on it, repeat it, etc.

### "Make it possible" means the tool must be _simple_

Below is a hammer that you can use to drive a nail (the task of interest) at nearly any skill level:

<img src="/images/claw_hammer.jpg" width="450">

That is what we are shooting for in this lesson.

Below is what git gives you out of the box:

<img src="/images/swiss_army_hammer.jpg" width="450">

Obviously, this tool is too complicated. Each individual component is probably very useful, but it's so confusing as to be useless until you know how to use each, and every, one of those attachments.
We ain't using this hammer here. Because it's confusing. And confusing is worthless for beginners needing to get something done.

Instead, this lesson will focus on a narrow subset of what git can do to make it more approachable (the "Goat Path Git"). Our view is that, as researchers, you are probably pretty good at, well, _researching_ how to fix a problem. If we can get you started using some basic aspects of the tool (git), you will be prepared to learn what you need to make the most of it later!

-----------------------------------------------------------------------------------------------------------------------------
## The Goat Path
According to the OED, a goat path is: A (narrow) path or track, especially on a hillside or mountain, such as is made by goats.

Here we take a narrow path in describing git that is useful for researchers who want help with version control for their day-to-day professional lives.

### Why a goat path?
Well a goat path can be the shortest (and possibly the safest) path to follow in a remote place you're not familiar with. And let's face it, git is unfamiliar territory! The beauty of a goat path is that those who know their way around (the goats) have traveled the same way so many times before that it's actually cut a visible and easy-to-follow trail. You know this trail is safe because, if it weren't, the goats would not have gone that way in the first place.

In case you've never seen a goat path before: this is one.

<img src="/images/goat_path.jpg" width="450">

If you don't follow the goat path as a beginner, bad things happen sometimes. This is so common with git that the popular comic XKCD has even commented on it.

<img src="/images/git_xkcd.png" width="450">

[Comic by XKCD](https://xkcd.com/1597/)

***Please note:*** there has been no mention of coding above. That's on purpose; git can be used to perform version control on regular text (manuscripts, dissertations, theses, etc), data (though there are many, many other [probably better] ways to do this), as well as code! Versioning is great. And versioning is really the whole point here. Git just happens to be the tool we use (but there are many other options, go explore!).

------------------------------------------------------------------------------------------------------------------------------
## So...what is Git?
Git is powerful software to help you with version control and collaboration. That is, git helps you to track and organize changes to your files over time, revisit prior versions of files, and collaborate with others. Git is built for the command line (although it can be managed through various GUIs - [click here for more](https://git-scm.com/downloads/guis)).

## Ok, so what is GitHub then?
GitHub (and other such platforms) is an online place to facilitate that version control, collaboration, and publication of your work in accordance with the ideals of "open science". They host and manage the servers so you don't have to.

Let me be clear: Git is *not the same thing* as GitHub! Git is a tool you can use from the command line. It is something you can use on your local machine without ever interacting with GitHub or any other service like it. GitHub, however, is a service/resource that makes using certain aspects of git easier.

### Why GitHub, and not some other service?
Software Carpentries likes GitHub for a few reasons, but perhaps the best reason is that it is very popular! And when collaboration is one of the goals, popular is a good thing :sunglasses:

Plus, if you're a student, you can have unlimited private repositories with GitHub for the duration of your studentship :nerd_face:
