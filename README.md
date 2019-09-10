# Git Branch, Pull, and Fetch
## Git Branch
One of the most powerful things about git is the ability to branch off from the main “trunk” of the code in which to create a new feature, test some new concept, upgrade packages, etc.

This is super powerful because it gives us as a team of developers the ability to work somewhat agnostic of other team members in our own little code world.  I as a developer can branch off of some other branch and I am now in my own little repo world I can make changes, I can break things, etc without fear of accidentally pushing up my code to the “source of truth” branch and potentially getting a bug deployed into production.

### The Commands
#### Git Branch
[Git - git-branch Documentation](https://git-scm.com/docs/git-branch)

```
git branch ...[all the things]
```

Git Branch has LOTS of arguments that can be applied but the ones I use the most are:
```
git branch -l or —list
git branch -D [branch-to-delete]
```

#### Git Checkout
[Git - git-checkout Documentation](https://git-scm.com/docs/git-checkout)

```
git checkout [-q] [-f] [-m] [<branch>]
```

Like Git Branch, Checkout has lots of powerful switches and arguments but below are the ones I use the most:

```
git checkout [existing-branch-name]
git checkout -b [new-branch-name]
```
