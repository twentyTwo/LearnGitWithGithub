The --no-ff option ensures that a fast forward merge will not happen, and that a new commit object will always be created. This can be desirable if you want git to maintain a history of feature branches.      

![](https://i.stack.imgur.com/FMD5h.png)

In the above image, the left side is an example of the git history after using `git merge --no-ff` and the right side is an example of using git merge where an ff merge was possible.

**EDIT:** A previous version of this image indicated only a single parent for the merge commit. Merge commits have multiple parent commits which git uses to maintain a history of the "feature branch" and of the original branch. The multiple parent links are highlighted in green.

