## Git Reset Command
- we will see how to revert to either the last commit or any other commit using the commit ID.
- I have created a file called Readme.md.
- we add this line for the second commit.
- git reset "commit ID to get back to" --hard

## Git Revert Command

- Unlike git reset command, git revert command creates a new commit for the reverted changes. The commit where we reverted from will not be deleted.
- git revert "latest commit" with a message as it will create a new commit.

## Difference between Git Reset and Git Revert : 
- git reset deletes the reverted commit, but git revert doesnt;
- git reset does not create a new commit, but git revert does;

## When to use git reset and git revert ; 
- You should use git reset till you havent push the commits. Once you have pushed then use git revert to revert the changes.