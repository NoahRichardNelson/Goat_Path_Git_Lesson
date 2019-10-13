# Gitting started
We need to make sure both *git* and *GitHub* are set up for use!

## Make sure you have a GitHub account and can log into it!
If you have not yet created a GitHub account, please do so now! [github.com](https://github.com)

Pay attention to your *user name* and your *user email*. You will need these later :grin:
It is recommended that you *use your UA email*.

## Make sure you have git installed on your computer!
To check if you have (the right version of) git installed, open a command line and do:
`git --version`

You should get an output like this:
``

If you get an error or nothing happens, you need to install git! [Visit the workshop homepage and find the git installation instructions](https://ua-carpentries-workshops.github.io/2019-10-26-Tucson/).

##
It's time to create our first repository!
1. Make a directory called 'NAME' (mkdir)
2. `git init` to initialize the directory as a git repository
3. `ls -la` to ensure that a .git/ hidden directory was created. This tells you that this is a git repository
4. `git config --global user.name='YOUR NAME HERE'`
5. `git config --global user.email='YOUR EMAIL HERE'`

Oh, that was easy!
-----------------------------------------------------------------------------------------------------------------------------
## The Goat Path
This git lesson for researchers is based on the "Goat Path" concept. The Oxford definition of goat path is: A (narrow) path or track, especially on a hillside or mountain, such as is made by goats. Here we take a narrow path in describing git that is useful for researchers who need versioning in their day-to-day professional lives.

Why a goat path? Well a goat path can be the shortest (and possibly the safest) path to follow in a remote place you're not familiar with; this is exactly how researchers learning code often feel about versioning technologies. The beauty of a goat path is that something (quite possibly actual goats) has followed that specific path so many times it's actually cut a visible and easy to follow trail. If it wasn't safe, it's very likely the path wouldn't get cut in the first place, because those things wouldn't be able to retread their path over and over again.

In case you've never seen a goat path before: this is one.

<img src="/images/goat_path.jpg" width="450">

If you don't follow the goat path as a beginner, bad things happen sometimes. This is so common with git that the popular comic XKCD has even commented on it.

<img src="/images/git_xkcd.png" width="450">

[Comic by XKCD](https://xkcd.com/1597/)


***Please note:*** there has been no mention of coding above. That's on purpose; git can be used to perform version control on regular text (manuscripts, dissertations, theses, etc), data (though there are many, many other [probably better] ways to do this), as well as code! Versioning is great. And versioning is really the whole point here. Git just happens to be the tool we use (but there are many other options, go explore!).


# PRIOR CONTENT, KEPT FOR NOW
## Gitting Set up on a Computer (get it?)
Be sure that git is installed on the computer. Installation details found on [Google](https://duckduckgo.com/?q=never+gonna+give+you+up+video+autoplay+not+on+youtube&t=ffab&ia=videos&iax=videos&iai=dQw4w9WgXcQ).
1. Create a repository on GitHub
2. Copy URL for the repository
3. `git clone URL` in a directory on whatever computer we're using so we can work with the repo.
4. Now we're all set on the machine you're working on. From here on out it's a cycle.

## The Goat Path Git Cycle
1. Do some things with the repository (e.g. change code, update the files inside, move things around, etc).
2. `git status` to assess changes to the repository.
3. `git add filename` stage changes for a commit. If you're 100% sure you like all the changes in a repo you can use `git add --all` (`git add -A` for short) to stage every change in the repo.
4. `git status` again. This will show you what you're getting ready to commit. This is super useful!
5. `git commit -m "add a useful message for later here about your checkpoint commit"` to finalize the changes as a commit. This is now a single checkpoint you can always get back to (on the computer you're working on only!).
6. `git push` to GitHub to save your commit out on the web where you can get at it later on some other computer. Also your collaborators can find it there too (and the entire world if it's public!).
7. Start the cycle over again with changing things in the repo (step 1 in the Goat Path Git Cycle).


# Compendium of Git Functions Used
- git clone
- git status
- git add
- git commit
- git push

# Frequently Asked Question
## Where can I go to find more training for Git after these intro lessons?
Great question. If you're at the University of Arizona there are organizations that can help: Research Bazaar Arizona. There's also an more advanced git lesson in this organization's profile.



# Frequently "Asked" Questions

## I really don't like what you're doing here. If you don't teach researchers $X git function, they're not going to be able to do $"cool thing"/$"survive"/$"be amazing".
Research has been happening for hundreds of years before versioning tools. I think they'll be fine. I'm just trying to teach them something that'll make their life a bit easier.

## You're playing with forces you can't possibly understand!
You're right. I'm a researcher; I do that every day.
