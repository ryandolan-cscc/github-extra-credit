# github-extra-credit
 
* *How do you see the files changed within each commit from git log?*

**git diff --name-only** followed by the commit id

* *How do you see the contents of what changed within each file from the git log?*

**git diff** followed by the commit id

* *What does HEAD refer to in the context of git? (Not to be confused with the "HEAD<<<<" one observes within merge conflict)*

When you **git checkout**, it is the last commit that occurred when you checked out.
