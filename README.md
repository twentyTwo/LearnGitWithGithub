[Using https://jbt.github.io/markdown-editor/]

# Learn the Advance Concepts of Git

 Topics
-
* [`git merge` vs `git merge --no-ff`] (https://stackoverflow.com/questions/9069061/what-is-the-difference-between-git-merge-and-git-merge-no-ff)
* [10 advance git commands] (https://towardsdatascience.com/10-git-commands-you-should-know-df54bea1595c)

*[Edit commit message ] (https://gist.github.com/nepsilon/156387acf9e1e72d48fa35c4fabef0b4)

* See the parent branch of current branch
  - Add an alias in git config file
    [alias]
            parent = "!git show-branch | grep '*' | grep -v \"$(git rev-parse --abbrev-ref HEAD)\" | head -n1 | sed 's/.*\\[\\(.*\\)\\].*/\\1/' | sed 's/[\\^~].*//' #"
            
    Then, `git parent`
  
