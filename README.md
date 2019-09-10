# Git Branch, Pull, and Fetch
## Git Branch
One of the most powerful things about git is the ability to branch off from the main “trunk” of the code in which to create a new feature, test some new concept, upgrade packages, etc.

This is super powerful because it gives us as a team of developers the ability to work somewhat agnostic of other team members in our own little code world.  I as a developer can branch off of some other branch and I am now in my own little repo world I can make changes, I can break things, etc without fear of accidentally pushing up my code to the “source of truth” branch and potentially getting a bug deployed into production.

## Git Pull
Git pull is the ability to pull updated code from an `upstream` to your local version of the repository. `git pull` is _actually_ shorthand for `git fetch`  and `git merge`

### The Command
[Git - git-pull Documentation](https://git-scm.com/docs/git-pull)
```
git pull [<options>] [<repository> [<refspec>…​]]
```

Options are a plenty.  

## Git Fetch
“Fetch branches and/or tags (collectively, “refs”) from one or more other repositories, along with the objects necessary to complete their histories. Remote-tracking branches are updated.”

### The Command
[Git - git-fetch Documentation](https://git-scm.com/docs/git-fetch)
```
git fetch [<options>] [<repository> [<refspec>...]]
```

## Git Merge
This is a powerful part of Git.  And with great power comes great responsibility.  Merging takes two histories and literally “merges” them together.  Frequently git can do this automatically for us by “fast-forwarding” the commits and all is well.  However, sometimes you may have edited a file that someone else edited at approximately the same line causing git to have a merge conflict.  These must be resolved.

### The Command
 [https://git-scm.com/docs/git-merge](https://git-scm.com/docs/git-merge) 
```
git merge [<options>] [<commit>...]
```

