# Gitting started
We need to make sure both *git* and *GitHub* are set up for use!

## Make sure you have a GitHub account and can log into it!
If you have not yet created a GitHub account, please do so now! [github.com](https://github.com)

Pay attention to your *user email* for GitHub. You will need it later :grin:
It is recommended that you *use your UA email*, but it is not necessary.

## Make sure you have git installed on your computer!
To check if you have (the right version of) git installed, open a command line and do:
`git --version`

You should get an output like this:
`git version 2.23.0`

(Any 2.x version should be fine)

If you get an error or nothing happens, you need to install git! [Visit the workshop homepage here to find the git installation instructions](https://ua-carpentries-workshops.github.io/2019-10-26-Tucson/).

## Green stickies when ready, red if you need help!

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
