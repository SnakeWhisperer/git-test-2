This repo is a test for learning how to use Git and GitHub. It was initialized with no files and no commits on GitHub and initialized with this README file on the command line.
The commands used for its initialization are the following:

```
$ git init
$ git add README.md
$ git commit -m "first commit"
$ git remote add origin https://github.com/SnakeWhisperer/git-test-2.git
$ git push -u origin master
```

Note that this differs from what GitHub recommends when creating the repo from the command line. No 'main' branch is created and the push is made from the initial 'master' branch in the local repo.
This is done to see what consequences it has.

When this file is created like this, locally, its presentation in GitHub is not what one would expect. The newlines in the commands part are not really there.
Another thing to notice is that, pushing this way, creates a 'master' branch in the remote repo with the 'first commit' (the one created locally) and there seems to be no problem.
